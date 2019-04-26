---
title: Идентифицират Изтрий съобщението събития в регистрационните файлове от одита
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1370
ms.assetid: ''
ms.openlocfilehash: 93f8a192af6e689e2b2d04013f35b8da2b69e607
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: bg-BG
ms.lasthandoff: 04/23/2019
ms.locfileid: "32416699"
---
# <a name="audit-logs-for-deleted-email-messages"></a><span data-ttu-id="36f1b-102">Регистрационните файлове за проверка за изтрити имейл съобщения</span><span class="sxs-lookup"><span data-stu-id="36f1b-102">Audit logs for deleted email messages</span></span>

<span data-ttu-id="36f1b-103">Започвайки през януари 2019, Microsoft е превръщането на пощенска кутия за влизане по подразбиране.</span><span class="sxs-lookup"><span data-stu-id="36f1b-103">Starting in January 2019, Microsoft is turning on mailbox audit logging by default.</span></span> <span data-ttu-id="36f1b-104">В противен случай за да прегледате Изтрий съобщението събития за определен потребител, трябва да разрешите ръчно изтриване действия за одит.</span><span class="sxs-lookup"><span data-stu-id="36f1b-104">Otherwise, to review delete message events for a specific user, you need to manually enable the delete actions for auditing.</span></span> <span data-ttu-id="36f1b-105">Ако пощенската кутия одит сеч е вече разрешено за вашата организация или за конкретен потребител, изпълнете следните стъпки.</span><span class="sxs-lookup"><span data-stu-id="36f1b-105">If mailbox audit logging is already enabled for your organization or for the specific user, follow the steps below.</span></span>

1. <span data-ttu-id="36f1b-106">Влезте в [Office 365 сигурност & съответствие център](https://protection.office.com/)</span><span class="sxs-lookup"><span data-stu-id="36f1b-106">Log in to the [Office 365 Security & Compliance Center](https://protection.office.com/)</span></span>

2. <span data-ttu-id="36f1b-107">Щракнете върху **търсене и проучване** и изберете **Одит регистрационния файл търсене**.</span><span class="sxs-lookup"><span data-stu-id="36f1b-107">Click **Search and Investigation** and select **Audit Log Search**.</span></span>

3. <span data-ttu-id="36f1b-108">Изберете диапазона от дати в полетата **Начална дата** и **крайна дата** .</span><span class="sxs-lookup"><span data-stu-id="36f1b-108">Select the date range in the **Start date** and **End date** fields.</span></span> <span data-ttu-id="36f1b-109">Задайте потребителското име на потребителя, който искате да разследва (потребител, който изтрити елементи).</span><span class="sxs-lookup"><span data-stu-id="36f1b-109">Specify username for the user that you want to investigate (the user who deleted the items).</span></span> <span data-ttu-id="36f1b-110">В областта на **дейности** изберете **изтритите съобщения от папката "Изтрити"** и **преместен съобщения към папката Изтрити елементи**.</span><span class="sxs-lookup"><span data-stu-id="36f1b-110">In the **Activities** field, select **Deleted messages from Deleted Items folder** and **Moved messages to Deleted Items folder**.</span></span>

4. <span data-ttu-id="36f1b-111">Щракнете върху **търсене**.</span><span class="sxs-lookup"><span data-stu-id="36f1b-111">Click **Search**.</span></span>

<span data-ttu-id="36f1b-112">В резултатите изберете отчет.</span><span class="sxs-lookup"><span data-stu-id="36f1b-112">In the results, select an audit record.</span></span> <span data-ttu-id="36f1b-113">В детайли flyout щракнете върху **Повече информация**.</span><span class="sxs-lookup"><span data-stu-id="36f1b-113">In the details flyout, click **More Information**.</span></span> <span data-ttu-id="36f1b-114">Допълнителна информация за изтрит елемент (например, темата и местоположението на артикула, когато тя е била изтрита) се показва в полето **AffectedItems** .</span><span class="sxs-lookup"><span data-stu-id="36f1b-114">Additional information about the deleted item (for example, the subject line and the location of the item when it was deleted) is displayed in the **AffectedItems** field.</span></span> <span data-ttu-id="36f1b-115">Свойството **ClientInfoString** ще покаже, ако заличаването настъпили в Outlook, Outlook в мрежата (известен преди като Outlook Web App), или всяко друго устройство.</span><span class="sxs-lookup"><span data-stu-id="36f1b-115">The **ClientInfoString** property will show if the deletion occurred in Outlook, Outlook on the web (formerly known as Outlook Web App), or any other device.</span></span>

<span data-ttu-id="36f1b-116">За повече информация вижте [определя кой създаде имейл спедиция за пощенска кутия](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#determining-if-a-user-deleted-email-items).</span><span class="sxs-lookup"><span data-stu-id="36f1b-116">For more information, see [Determining who set up email forwarding for a mailbox](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#determining-if-a-user-deleted-email-items).</span></span>

<span data-ttu-id="36f1b-117">**Забележка**: не можете да намерите изтритите елементи, с помощта на функцията за регистриране за одит.</span><span class="sxs-lookup"><span data-stu-id="36f1b-117">**Note**: You can't retrieve deleted items using the audit log feature.</span></span> <span data-ttu-id="36f1b-118">За да извлечете изтритите съобщения в Outlook в мрежата, вижте [възстановяване на изтрити елементи в Outlook Web App](https://support.office.com/article/C3D8FC15-EEEF-4F1C-81DF-E27964B7EDD4).</span><span class="sxs-lookup"><span data-stu-id="36f1b-118">To retrieve deleted messages in Outlook on the web, see [Recover deleted items in Outlook Web App](https://support.office.com/article/C3D8FC15-EEEF-4F1C-81DF-E27964B7EDD4).</span></span>