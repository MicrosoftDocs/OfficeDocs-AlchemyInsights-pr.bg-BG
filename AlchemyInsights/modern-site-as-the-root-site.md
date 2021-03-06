---
title: Модерен сайт като главен сайт
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ms.date: 04/21/2020
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000265"
- "1874"
ms.openlocfilehash: 86ff5f7fbaed62de9047006bf4ba4d2db2be3def
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: bg-BG
ms.lasthandoff: 09/14/2020
ms.locfileid: "47666859"
---
# <a name="modern-site-as-root-site"></a>Модерен сайт като главен сайт

Ние започнахме да внедряваме нова функция, която ще ви помогне да [размените своя класически сайт за главни сайтове с модерен сайт](https://docs.microsoft.com/sharepoint/modern-root-site). Използвайте " [SPOSiteSwap](https://docs.microsoft.com/powershell/module/sharepoint-online/invoke-spositeswap?view=sharepoint-ps) ", за да размените местоположението на сайт с друг сайт, докато архивирате първоначалния сайт. Налични и за двата екипа на сайта (не е свързан с група) и комуникационен сайт.

>[!Important]
> Не изтривайте класическия си главен сайт, за да създадете модерен комуникационен сайт. Това не се поддържа от Microsoft. Изтриването на главния сайт ще направи всички сайтове на SharePoint във вашата организация недостъпни за всички потребители, докато не възстановите сайта или не създадете нов сайт на един и същ URL адрес. Ще комуникираме с тази функция чрез центъра за съобщения. Би трябвало да очаквате тази функция да бъде включена в своя клиент скоро.

## <a name="known-issues-with-swapping-sites"></a>Известни проблеми със смяната на сайтове
- Целевият сайт може да върне грешка "не е намерен" (HTTP 404) за кратък период от време.
- Съдържанието ще трябва да бъде обходено, за да се актуализира индексът за търсене. Тук не се изисква ръчна стъпка, това ще бъде извършено автоматично.
- Всичко, което зависи от "статичните" връзки (като файлове за синхронизиране на файлове и OneNote), ще трябва да бъде коригирано ръчно.
- За да се гарантира, че те все още се асоциират правилно, може да се наложи да бъдат утвърдени сайтовете на Project Server. 
