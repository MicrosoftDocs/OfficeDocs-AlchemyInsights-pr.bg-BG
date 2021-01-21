---
title: Проблем с присъединяването към VMs
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 01/15/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "7924"
- "9004395"
ms.openlocfilehash: 77a889f05d6c4e7b19a1e0a66a99ffc0565c69d8
ms.sourcegitcommit: a61a29dbd0382370fea0be5fa4a61c9a1a9354c7
ms.translationtype: MT
ms.contentlocale: bg-BG
ms.lasthandoff: 01/18/2021
ms.locfileid: "49884859"
---
# <a name="issue-joining-vms"></a>Проблем с присъединяването към VMs

За да разрешите проблеми, които възникват, когато се опитвате да се присъедините към VMs, изпълнете следните стъпки:

1. Опитайте да влезете с формата **UPN** (например "joeuser@contoso.com") вместо формата **SAMAccountName** ("CONTOSO\joeuser").
2. Уверете се, че сте разрешили синхронизирането на пароли в съответствие със стъпките, описани в ръководството за *Първи стъпки* .
3. Уверете се, че засегнатите потребителски акаунти не са външни акаунти в Azure AD клиент. Външните потребители не могат да влязат в управлявания домейн, тъй като услугите за домейни на Azure AD нямат идентификационни данни за тези потребителски акаунти.
4. Ако засегнатият потребителски акаунт е потребителски акаунт само за облак, уверете се, че потребителите са променили паролата си, след като сте разрешили услугите за домейни на Azure AD. Тази стъпка кара да бъдат генерирани хеширане на идентификационни данни, необходими за Azure AD Domain Services.
5. Ако засегнатите потребителски акаунти са синхронизирани от локален справочен указател, се уверете, че препоръчваното издание на Azure AD Connect е конфигурирано за извършване на пълно синхронизиране.
6. Ако проблемите продължават след потвърждаване на стъпка 4, изпълнете следните команди от вашата машина за синхронизиране:
 
     `"net stop 'Microsoft Azure AD Sync'"`  
     `"net start 'Microsoft Azure AD Sync'"`.