---
title: Ръчно влизане в Microsoft Edge
ms.author: v-smandalika
author: v-smandalika
ms.date: 12/03/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 686e8f18-b871-4dd2-864f-8562947ab583
ms.collection: Adm_O365
ms.custom:
- "9003844"
- "6893"
ms.openlocfilehash: c5d71c26ba3584f8ce496a28587fe75cae2d344f
ms.sourcegitcommit: 94036315916fbc79dca2a692c2e9bc1139dd28f6
ms.translationtype: MT
ms.contentlocale: bg-BG
ms.lasthandoff: 12/08/2020
ms.locfileid: "49676834"
---
# <a name="sign-in-to-microsoft-edge-manually"></a>Ръчно влизане в Microsoft Edge

Ако потребителят не е влязъл автоматично по време на първокласна среда, потребителят може да влезе ръчно през настройките на браузъра или изплаващо за самоличност. За да управлявате влизане, използвайте следните правила:

1. [NonRemovableProfileEnabled](https://docs.microsoft.com/deployedge/microsoft-edge-policies#nonremovableprofileenabled) – за да се гарантира, че потребителят винаги има служебен профил в Microsoft Edge.
2. [RestrictSigninToPattern](https://docs.microsoft.com/deployedge/microsoft-edge-policies#restrictsignintopattern) – за да ограничите влизане в набор от надеждни акаунти.
3. [BrowserSignin](https://docs.microsoft.com/deployedge/microsoft-edge-policies#browsersignin) -за да забраните влизане или да принудите потребителите да влязат.

