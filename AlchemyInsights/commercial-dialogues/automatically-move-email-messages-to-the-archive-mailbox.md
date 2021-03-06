---
title: Автоматично преместене на имейл съобщения в архивната пощенска кутия
ms.author: v-jmathew
author: v-jmathew
manager: dansimp
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3100008"
- "7217"
ms.openlocfilehash: 14ded561ee2b3c244fadbdab42fd0e833a1c66d5
ms.sourcegitcommit: 6312ee31561db36104f32282d019d069ede69174
ms.translationtype: MT
ms.contentlocale: bg-BG
ms.lasthandoff: 03/11/2021
ms.locfileid: "50743354"
---
# <a name="automatically-move-email-messages-to-the-archive-mailbox"></a>Автоматично преместене на имейл съобщения в архивната пощенска кутия

Ето как да настроите правила за автоматично преместене на стария имейл на потребител в архивната пощенска кутия:

1. Отидете на страницата за защита за управление на данни в [**съответствие &**](https://go.microsoft.com/fwlink/p/?linkid=2077143)  >    >   , за да проверите дали е разрешена пощенска кутия за архивиране за потребителя. Ако не е, щракнете върху **Разреши** , а след това **да** в полето за предупреждение.
2. Отидете в [**центъра за администриране на Exchange > управление на съответствието > етикети за съхранение**](https://go.microsoft.com/fwlink/?linkid=2059104).
3. Изберете иконата +, след което изберете **автоматично прилагане към цялата пощенска кутия**.
4. Присвояване на име на етикет за съхранение и изберете **преминаване към архивиране**. За периода на съхранение въведете часа, който искате, като например 90 дни. Щракнете върху **Запиши**.
5. Сега създайте правила за съхранение: изберете **правила за съхранение**, изберете иконата, за да добавите нови правила.
6. Дайте име на правилата за съхранение, след което щракнете и превъртете, за да намерите и добавите етикета за съхранение, който току-що създадохте. Щракнете върху **Запиши**.
7. И накрая, приложете правилата за съхранение към пощенската кутия на потребителя: все още в центъра за администриране на Exchange, отидете на  >  **пощенските кутии** на получателите. Изберете всички потребители, за които искате да приложите правилата, след което изберете **Редактиране** (иконата на молив).
8. В диалоговия прозорец щракнете върху **функции за пощенската кутия**. Под **правила за съхранение** Приложете правилата, които току-що създадохте, > **запишете**.
9. За инструкции за прилагане на правилата към всички потребители вижте [прилагане на правила за съхранение към пощенски кутии](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/apply-retention-policy).
