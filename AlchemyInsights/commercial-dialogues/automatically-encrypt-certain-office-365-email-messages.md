---
title: Автоматично шифроване на определени имейл съобщения на Office 365
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 02/24/2021
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000078"
- "7342"
ms.openlocfilehash: e4b2f4ffcacf03e145b4c6d5ff6e73a75cb7c184
ms.sourcegitcommit: 6312ee31561db36104f32282d019d069ede69174
ms.translationtype: MT
ms.contentlocale: bg-BG
ms.lasthandoff: 03/11/2021
ms.locfileid: "50743366"
---
# <a name="automatically-encrypt-certain-office-365-email-messages"></a>Автоматично шифроване на определени имейл съобщения на Office 365

Можете автоматично да шифровате съобщения, изпратени от потребители до определени външни хора или организации. За да направите това, изпълнете следните стъпки:

1. От [центъра за администриране на Exchange](https://outlook.office365.com/ecp/)изберете " **пощенски поток" > правила**. 
2. Щракнете върху иконата **нова (+)** и след това щракнете върху **прилагане на шифроване на съобщения в Office 365 и защита на правата към съобщенията**.
3. В **име** въведете име за правилото, като например *шифроване на съобщения, изпратени до DrToniRamos@gmail.com*.
4. В **прилагане на това правило, ако** изберете **получателя > е този човек**. 
5. В диалоговия прозорец **избор на членове** изберете името на лицето, на което искате да се приложи правилото за шифроване, и след това щракнете върху **Добави**. 
6. Когато сте готови с добавянето на потребители, щракнете върху **OK**.
7. До полето **направете следното** щракнете върху **Избери една**. 
8. В падащото меню **RMS шаблон** изберете **шифроване** и след това щракнете върху **OK**. (Ако не виждате тази опция, това означава, че вашият план не включва автоматично шифроване. Но можете да го добавите.)
9. Изберете произволна селекция (от списък с допълнителни селекции, които можете да направите в този момент, като много от тях могат да бъдат оставени с настройката по подразбиране за улеснение).
10. Щракнете върху **Запиши**.

> [!IMPORTANT]
> Можете винаги да се върнете и да редактирате това правило по-късно.

За повече информация относно създаването на правила за шифроване вижте [определяне на правилата за пощенския поток за шифроване на имейл съобщения в Office 365](https://docs.microsoft.com/microsoft-365/compliance/define-mail-flow-rules-to-encrypt-email).

