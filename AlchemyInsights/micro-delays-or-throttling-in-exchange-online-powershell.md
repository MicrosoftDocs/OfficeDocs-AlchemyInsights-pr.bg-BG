---
title: Микро закъснения или ограничаване на PowerShell в Exchange Online
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "3500011"
- "5106"
ms.openlocfilehash: 55844747be27ea4ff8f538492e576195b3a5f0bb
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: bg-BG
ms.lasthandoff: 09/14/2020
ms.locfileid: "47743902"
---
# <a name="micro-delays-or-throttling-in-exchange-online-powershell"></a>Микро закъснения или ограничаване на PowerShell в Exchange Online

Възможно е да видите предупреждения за "Приложено микро забавяне" или закъснения, когато изпълнявате скриптове и кратки команди в Exchange Online. Ето две предложения, свързани с това:

- Може да поискате да се опитате да използвате [модула Exchange Online v2 PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/exchange-online-powershell-v2/exchange-online-powershell-v2?view=exchange-ps), който включва кратки команди, които са базирани на REST API и са значително по-подходящи. Това може да бъде чудесно решение за много от често използваните кратки команди.
- Ако трябва да използвате кратки команди, които все още не са включени в модула V2, вижте [Изпълнение на кратки команди на PowerShell за голям брой потребители в Office 365](https://techcommunity.microsoft.com/t5/exchange-team-blog/updated-running-powershell-cmdlets-for-large-numbers-of-users-in/ba-p/1000628#), където се говори за това как да се ориентирате в очакваните ограничения при PowerShell в Exchange Online.
