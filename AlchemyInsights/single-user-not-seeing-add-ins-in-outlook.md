---
title: Отделен потребител, който не вижда добавки в Outlook
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 07/16/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: ''
ms.openlocfilehash: 8c99b443a2d83f3ac24362d63cd6363a66a81393
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: bg-BG
ms.lasthandoff: 09/14/2020
ms.locfileid: "47719654"
---
# <a name="single-user-not-seeing-add-ins-in-outlook"></a>Отделен потребител, който не вижда добавки в Outlook

Потребителят може да бъде част от роля, която не съдържа правилния параметър на AppsForOfficeEnabled. Изпълнете тази кратка команда, за да разберете дали правилната роля е свързана с потребителя:

Get-ManagementRoleAssignment-RoleAssignee user@domain.com-делегиране на $false | Формат-таблица – автоматична роля, RoleAssigneeName, RoleAssigneeType

За повече информация вижте [Задаване на администраторите и потребителите, които могат да инсталират и управляват добавки за Outlook](https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/add-ins-for-outlook/specify-who-can-install-and-manage-add-ins).
