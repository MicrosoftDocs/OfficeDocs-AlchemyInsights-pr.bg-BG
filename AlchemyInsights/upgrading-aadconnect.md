---
title: 932 надстройване на AADConnect
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "932"
- "1300025"
ms.assetid: 8f43f36c-9722-43a4-b0de-c5341c06dac5
ms.openlocfilehash: fcc5fddb5cfd15407d0533449035317d187931ed
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: bg-BG
ms.lasthandoff: 04/22/2020
ms.locfileid: "43766482"
---
# <a name="upgrade-azure-ad-connect"></a><span data-ttu-id="ced30-102">Надграждане Azure AD свързване</span><span class="sxs-lookup"><span data-stu-id="ced30-102">Upgrade Azure AD Connect</span></span>

<span data-ttu-id="ced30-103">По подразбиране автоматичното надстройване е разрешено за свързване с Azure AD, което помага да се гарантира, че изпълнявате най-новата версия.</span><span class="sxs-lookup"><span data-stu-id="ced30-103">By default, automatic upgrade is enabled for Azure AD Connect, which helps to ensure you're running the latest version.</span></span> <span data-ttu-id="ced30-104">За да проверите настройките за автоматично надграждане, използвайте кратката команда **Get-ADSyncAutoUpgrade** в Azure AD PowerShell.</span><span class="sxs-lookup"><span data-stu-id="ced30-104">To verify the automatic upgrade settings, use the **Get-ADSyncAutoUpgrade** cmdlet in Azure AD PowerShell.</span></span> <span data-ttu-id="ced30-105">Кратката команда ще върне една от следните стойности:</span><span class="sxs-lookup"><span data-stu-id="ced30-105">The cmdlet will return one of following values:</span></span>

- <span data-ttu-id="ced30-106">**Разрешено:** Автоматичното надстройване е разрешено.</span><span class="sxs-lookup"><span data-stu-id="ced30-106">**Enabled**: Automatic upgrade is enabled.</span></span>

- <span data-ttu-id="ced30-107">**Забранено:** Автоматичното надстройване е забранено.</span><span class="sxs-lookup"><span data-stu-id="ced30-107">**Disabled**: Automatic upgrade is disabled.</span></span>

- <span data-ttu-id="ced30-108">**Временно:** Системата вече не отговаря на условията за автоматично надстройване.</span><span class="sxs-lookup"><span data-stu-id="ced30-108">**Suspended**: The system is no longer eligible to receive automatic upgrades.</span></span> <span data-ttu-id="ced30-109">Не можете да конфигурирате тази стойност; тя е зададена от системата.</span><span class="sxs-lookup"><span data-stu-id="ced30-109">You can't configure this value; it's set by the system.</span></span>

<span data-ttu-id="ced30-110">За повече информация вижте [Автоматично надстройване](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-automatic-upgrade).</span><span class="sxs-lookup"><span data-stu-id="ced30-110">For more information, see [Automatic upgrade](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-automatic-upgrade).</span></span>

<span data-ttu-id="ced30-111">За да изтеглите най-новата версия [https://www.microsoft.com/download/details.aspx?id=47594](https://www.microsoft.com/download/details.aspx?id=47594)на Azure AD connect, отидете на .</span><span class="sxs-lookup"><span data-stu-id="ced30-111">To download the latest version of Azure AD Connect, go to [https://www.microsoft.com/download/details.aspx?id=47594](https://www.microsoft.com/download/details.aspx?id=47594).</span></span>
