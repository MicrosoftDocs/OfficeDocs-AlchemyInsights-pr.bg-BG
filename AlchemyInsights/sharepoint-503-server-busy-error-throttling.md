---
title: Онлайн ограничаване на SharePoint
ms.author: pebaum
author: pebaum
ms.date: 9/17/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: b376d8ea-50c4-47f0-9720-50d80aa3f7f1
ms.custom:
- "9000149"
- "1662"
- "3491"
ms.openlocfilehash: 59104ef96c95de4e4bc7744825245bdafba97d7c
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: bg-BG
ms.lasthandoff: 03/24/2020
ms.locfileid: "42931215"
---
# <a name="sharepoint-online-throttling"></a><span data-ttu-id="5ed19-102">Онлайн ограничаване на SharePoint</span><span class="sxs-lookup"><span data-stu-id="5ed19-102">SharePoint Online Throttling</span></span>

<span data-ttu-id="5ed19-103">**Важно:** много sharePoint Online и OneDrive клиенти работят критични бизнес приложения срещу услугата, която се изпълнява във фонов режим.</span><span class="sxs-lookup"><span data-stu-id="5ed19-103">**Important**: Many SharePoint Online and OneDrive customers run business-critical applications against the service that run in the background.</span></span> <span data-ttu-id="5ed19-104">Те включват миграция на съдържанието, предотвратяване на загуба на данни (DLP) и архивиране на решения.</span><span class="sxs-lookup"><span data-stu-id="5ed19-104">These include content migration, Data Loss Prevention (DLP), and backup solutions.</span></span> <span data-ttu-id="5ed19-105">По време на тези безпрецедентни времена ние предприемаме стъпки, за да гарантираме, че SharePoint Online и OneDrive услуги остават високо достъпни и надеждни за вашите потребители, които зависят от услугата повече от всякога в отдалечени работни сценарии.</span><span class="sxs-lookup"><span data-stu-id="5ed19-105">During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available and reliable for your users who depend on the service more than ever in remote work scenarios.</span></span>

<span data-ttu-id="5ed19-106">В подкрепа на тази цел, ние сме внедрили по-строги ограничения за ограничаване на приложенията за фон (миграция, DLP и архивиране на решения) през делничните дни.</span><span class="sxs-lookup"><span data-stu-id="5ed19-106">In support of this objective, we have implemented tighter throttling limits on background apps (migration, DLP and backup solutions) during weekday daytime hours.</span></span> <span data-ttu-id="5ed19-107">Трябва да очаквате, че тези приложения ще постигнат много ограничена пропускателна информация по време на тези времена.</span><span class="sxs-lookup"><span data-stu-id="5ed19-107">You should expect that these apps will achieve very limited throughput during these times.</span></span> <span data-ttu-id="5ed19-108">Въпреки това, по време на вечерните и почивните часове за региона, услугата ще бъде готова да обработи значително по-голям обем заявки от приложения за фон.</span><span class="sxs-lookup"><span data-stu-id="5ed19-108">However, during evening and weekend hours for the region, the service will be ready to process a significantly higher volume of requests from background apps.</span></span>

<span data-ttu-id="5ed19-109">**503 сървърът е зает грешка**</span><span class="sxs-lookup"><span data-stu-id="5ed19-109">**503 server is busy error**</span></span>

<span data-ttu-id="5ed19-110">Потребителите може да получат 503 сървър е заето грешка при опит да отидете до сайтове на SharePoint или OneDrive.</span><span class="sxs-lookup"><span data-stu-id="5ed19-110">Users may receive a 503 server is busy error when attempting to navigate to SharePoint or OneDrive sites.</span></span> 

<span data-ttu-id="5ed19-111">Тази грешка може да бъде причинена от ограничаване в рамките на услугата на SharePoint.</span><span class="sxs-lookup"><span data-stu-id="5ed19-111">This error can be caused by throttling within the SharePoint service.</span></span> <span data-ttu-id="5ed19-112">SharePoint Online използва дроселиране да поддържа оптимално производителност и надеждност на услугата на SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="5ed19-112">SharePoint Online uses throttling to maintain optimal performance and reliability of the SharePoint Online service.</span></span> <span data-ttu-id="5ed19-113">Ограничаването ограничава броя на действията на потребителя или едновременните повиквания (със скрипт или код), за да се предотврати превес на ресурсите.</span><span class="sxs-lookup"><span data-stu-id="5ed19-113">Throttling limits the number of user actions or concurrent calls (by script or code) to prevent overuse of resources.</span></span> 

<span data-ttu-id="5ed19-114">За повече информация относно ограничаване вижте, [Избягвайте да се дросели или блокирани в SharePoint Online](https://docs.microsoft.com/sharepoint/dev/general-development/how-to-avoid-getting-throttled-or-blocked-in-sharepoint-online).</span><span class="sxs-lookup"><span data-stu-id="5ed19-114">For more information on throttling see, [Avoid getting throttled or blocked in SharePoint Online](https://docs.microsoft.com/sharepoint/dev/general-development/how-to-avoid-getting-throttled-or-blocked-in-sharepoint-online).</span></span>

<span data-ttu-id="5ed19-115">Ако смятате, че тази грешка не е свързана с дроселиране, можете да проверите дали има активна поддръжка, която се извършва на вашия клиент, като отидете до центъра за [съобщения](https://portal.office.com/adminportal/home#/MessageCenter).</span><span class="sxs-lookup"><span data-stu-id="5ed19-115">If you believe this error is unrelated to throttling, you can check if there is active maintenance occurring on your tenant by navigating to the [Message center](https://portal.office.com/adminportal/home#/MessageCenter).</span></span>

 <span data-ttu-id="5ed19-116">Накрая, уверете се, че посещавате страницата ["Състояние на услугата",](https://portal.office.com/adminportal/home#/servicehealth) за да проверите за евентуални терапии/инциденти.</span><span class="sxs-lookup"><span data-stu-id="5ed19-116">Finally, ensure you visit the [Service Health](https://portal.office.com/adminportal/home#/servicehealth) page to check for any advisories/incidents that may be occurring.</span></span>

