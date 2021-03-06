---
title: Възстановяване на изтрита публична папка
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3500007"
- "3488"
ms.openlocfilehash: bb7fe248714e9a7e7f4c48913b159b5c23132192
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: bg-BG
ms.lasthandoff: 09/15/2020
ms.locfileid: "47774520"
---
# <a name="restore-a-deleted-public-folder"></a>Възстановяване на изтрита публична папка

**За да възстановите изтрити елементи от публична папка**:

- Вижте не можете [да възстановите изтрити елементи от публична папка, която не е поща, в Outlook 2016](https://aka.ms/pfrec).
 
**За да възстановите изтрита публична папка (от всякакъв тип)**: 

- Моля, използвайте следната команда на командата:

    Синтаксис

     `$pf=Get-PublicFolder \NON_IPM_SUBTREE\DUMPSTER_ROOT -Recurse  | ?{$_.Name -eq "\<name_of_deleted_public_Folder"};Set-PublicFolder $pf.identity -Path \<path where the folder will be restored>`

    Пример: следната команда ще възстанови Subfolder1 и да я постави под \Parent1:

    `$pf=Get-PublicFolder \NON_IPM_SUBTREE\DUMPSTER_ROOT -Recurse | ?{$_.Name -eq "Subfolder1"};Set-PublicFolder $pf.identity -Path \Parent1`

Вижте [възстановяване на изтрита публична папка](https://docs.microsoft.com/exchange/collaboration-exo/public-folders/restore-deleted-public-folder) за повече информация.
