---
title: Отстраняване на неизправности Достъпът отказан съобщения за OneDrive за бизнес сайтове
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.assetid: cebb7a4a-33e1-474e-a5d0-dbd02a80b1e9
ms.openlocfilehash: 95bd46e8b7a6006f3735612d9a5602fb2b2a283b
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: bg-BG
ms.lasthandoff: 06/02/2020
ms.locfileid: "44511173"
---
# <a name="troubleshooting-access-denied-messages-to-onedrive-for-business-sites"></a><span data-ttu-id="0c754-102">Отстраняване на неизправности Достъпът отказан съобщения за OneDrive за бизнес сайтове</span><span class="sxs-lookup"><span data-stu-id="0c754-102">Troubleshooting Access denied messages to OneDrive for Business sites</span></span>

<span data-ttu-id="0c754-103">Този проблем най-често възниква, когато потребителят се изтрива и създава отново със същото основно потребителско име (UPN).</span><span class="sxs-lookup"><span data-stu-id="0c754-103">This issue most frequently occurs when a user is deleted and re-created with the same user principal name (UPN).</span></span> <span data-ttu-id="0c754-104">Новият акаунт се създава с различна стойност puid (паспорт уникален ИД).</span><span class="sxs-lookup"><span data-stu-id="0c754-104">The new account is created by using a different PUID (Passport Unique ID) value.</span></span> <span data-ttu-id="0c754-105">Когато потребителят се опита да получите достъп до колекция от сайтове или своя OneDrive, потребителят е неправилен PUID.</span><span class="sxs-lookup"><span data-stu-id="0c754-105">When the user tries to access a site collection or their OneDrive, the user has an incorrect PUID.</span></span> <span data-ttu-id="0c754-106">Втори сценарий включва указатели с Active Directory организационна единица (ОЕ).</span><span class="sxs-lookup"><span data-stu-id="0c754-106">A second scenario involves directory synchronization with an Active Directory organizational unit (OU).</span></span> <span data-ttu-id="0c754-107">Ако потребителите вече са влезли в SharePoint и след това се преместват в друг ОЕ и resynced SharePoint, те може да се появи този проблем.</span><span class="sxs-lookup"><span data-stu-id="0c754-107">If users have already signed in to SharePoint, and then are moved to a different OU and resynced with SharePoint, they may experience this problem.</span></span>

1. <span data-ttu-id="0c754-108">За да разрешите този проблем, трябва да възстановите първоначалния UPN със стъпките в статията, възстановяване на [потребител в Microsoft 365](https://docs.microsoft.com/microsoft-365/admin/add-users/restore-user).</span><span class="sxs-lookup"><span data-stu-id="0c754-108">To resolve this issue you should restore the original UPN with the steps in the article, [Restore a user in Microsoft 365](https://docs.microsoft.com/microsoft-365/admin/add-users/restore-user).</span></span>
2. <span data-ttu-id="0c754-109">Ако не можете да възстановите първоначалния потребител трябва да премахнете стария потребител от oneDrive сайта с помощта на тези стъпки, [Премахване на потребител от списъка с информация за потребителя]().</span><span class="sxs-lookup"><span data-stu-id="0c754-109">If you cannot restore the original user you should remove the old user from the OneDrive site using these steps, [Remove a user from the user info list]().</span></span> 
3. <span data-ttu-id="0c754-110">След това можете да проверите потребителят има администраторски права на oneDrive сайт, като следвате стъпките за [Добавяне на администратор за потребител OneDrive](https://docs.microsoft.com/sharepoint/manage-user-profiles)</span><span class="sxs-lookup"><span data-stu-id="0c754-110">After this is done, you can verify the user has admin rights to the OneDrive site by following the steps to [Add admin's for a user's OneDrive](https://docs.microsoft.com/sharepoint/manage-user-profiles)</span></span>

<span data-ttu-id="0c754-111">За повече информация относно нивата на разрешение вижте [статията, Разбиране нивата на разрешенията в SharePoint](https://docs.microsoft.com/sharepoint/understanding-permission-levels).</span><span class="sxs-lookup"><span data-stu-id="0c754-111">For more information on permission levels, see the article, [Understanding permission levels in SharePoint](https://docs.microsoft.com/sharepoint/understanding-permission-levels).</span></span>
