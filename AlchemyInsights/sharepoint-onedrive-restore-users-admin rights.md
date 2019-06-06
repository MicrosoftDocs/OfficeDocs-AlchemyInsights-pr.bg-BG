---
title: Дават на потребителите достъп до SharePoint и OneDrive
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.date: 11/14/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: cebb7a4a-33e1-474e-a5d0-dbd02a80b1e9
ms.openlocfilehash: 9326932e93970edc96396a141c9b36b14e7b4d4d
ms.sourcegitcommit: 241e21b6da226563bf70bdb1f5bad3d91c38cd2c
ms.translationtype: MT
ms.contentlocale: bg-BG
ms.lasthandoff: 06/05/2019
ms.locfileid: "34736637"
---
# <a name="give-users-access-to-sharepoint-and-onedrive"></a><span data-ttu-id="647c7-102">Дават на потребителите достъп до SharePoint и OneDrive</span><span class="sxs-lookup"><span data-stu-id="647c7-102">Give users access to SharePoint and OneDrive</span></span>

<span data-ttu-id="647c7-103">Този проблем най-често се случва, когато даден потребител е изтрита и създадена отново със същото основно име на потребителя (UPN).</span><span class="sxs-lookup"><span data-stu-id="647c7-103">This issue most frequently occurs when a user is deleted and re-created with the same user principal name (UPN).</span></span> <span data-ttu-id="647c7-104">Новият акаунт е създаден с помощта на различни PUID (паспорт уникален ИД) стойност.</span><span class="sxs-lookup"><span data-stu-id="647c7-104">The new account is created by using a different PUID (Passport Unique ID) value.</span></span> <span data-ttu-id="647c7-105">Когато потребителят се опитва да получи достъп до колекция от сайтове или техните OneDrive, потребителят има неправилен PUID.</span><span class="sxs-lookup"><span data-stu-id="647c7-105">When the user tries to access a site collection or their OneDrive, the user has an incorrect PUID.</span></span> <span data-ttu-id="647c7-106">Вторият сценарий включва директория синхронизация с Active Directory организационни единици (OU).</span><span class="sxs-lookup"><span data-stu-id="647c7-106">A second scenario involves directory synchronization with an Active Directory organizational unit (OU).</span></span> <span data-ttu-id="647c7-107">Ако потребителите са вече влезли в SharePoint, след това се премества в различни OU и resynced с SharePoint, те могат да срещнат този проблем.</span><span class="sxs-lookup"><span data-stu-id="647c7-107">If users have already signed in to SharePoint, and then are moved to a different OU and resynced with SharePoint, they may experience this problem.</span></span>

<span data-ttu-id="647c7-108">За да разрешите този проблем трябва да възстановите оригиналния UPN със стъпките в статията,[възстановяване на потребител в Office 365](https://docs.microsoft.com/en-us/office365/admin/add-users/restore-user?view=o365-worldwide).</span><span class="sxs-lookup"><span data-stu-id="647c7-108">To resolve this issue you should restore the original UPN with the steps in the article,[Restore a user in Office 365](https://docs.microsoft.com/en-us/office365/admin/add-users/restore-user?view=o365-worldwide).</span></span>

<span data-ttu-id="647c7-109">След това е направено, можете да проверите потребителят има права на администратор на сайта на OneDrive като следвате стъпките за [Добавяне администратор на за потребителски OneDrive](https://docs.microsoft.com/en-us/sharepoint/manage-user-profiles?redirectSourcePath=%252fen-us%252farticle%252fmanage-user-profiles-in-the-sharepoint-admin-center-494bec9c-6654-41f0-920f-f7f937ea9723#add-and-remove-admins-for-a-users-onedrive)</span><span class="sxs-lookup"><span data-stu-id="647c7-109">After this is done, you can verify the user has admin rights to the OneDrive site by following the steps to [Add admin's for a user's OneDrive](https://docs.microsoft.com/en-us/sharepoint/manage-user-profiles?redirectSourcePath=%252fen-us%252farticle%252fmanage-user-profiles-in-the-sharepoint-admin-center-494bec9c-6654-41f0-920f-f7f937ea9723#add-and-remove-admins-for-a-users-onedrive)</span></span>

<span data-ttu-id="647c7-110">За повече информация за нивата на разрешения вижте статията, [разбиране на нивата на разрешение в SharePoint](https://docs.microsoft.com/en-us/sharepoint/understanding-permission-levels).</span><span class="sxs-lookup"><span data-stu-id="647c7-110">For more information on permission levels, see the article, [Understanding permission levels in SharePoint](https://docs.microsoft.com/en-us/sharepoint/understanding-permission-levels).</span></span>
