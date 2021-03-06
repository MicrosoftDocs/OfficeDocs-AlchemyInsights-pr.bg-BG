---
title: Промяна на изискването за силна парола
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
- "9000105"
- "1600"
ms.openlocfilehash: 8ce331275e066b5a4f177ae27178ec726f90762f
ms.sourcegitcommit: aa35d2e1829f7d07f64fb891bf73b1fd80f0864c
ms.translationtype: MT
ms.contentlocale: bg-BG
ms.lasthandoff: 10/30/2020
ms.locfileid: "48804412"
---
# <a name="change-strong-password-requirement"></a>Промяна на изискването за силна парола

Microsoft изисква сигурни пароли по подразбиране.

Чрез PowerShell можете да забраните сигурните пароли за определени потребители със следните команди:

`Set-MsolUser –UserPrincipalName <UserPrincipalName> –StrongPasswordRequired  $false`

За да забраните силните пароли за всички потребители, използвайте:

`Get-MsolUser | Set-MsolUser -StrongPasswordRequired $false`

- [Още информация за правилата за пароли](https://docs.microsoft.com/azure/active-directory/authentication/concept-sspr-policy#password-policies-that-only-apply-to-cloud-user-accounts)
- [Как да се свържете с Microsoft 365 с PowerShell](https://docs.microsoft.com/office365/enterprise/powershell/connect-to-office-365-powershell#connect-with-the-microsoft-azure-active-directory-module-for-windows-powershell)
- [Още информация за командите на PowerShell MsolUser](https://docs.microsoft.com/powershell/module/msonline/set-msoluser?view=azureadps-1.0)
