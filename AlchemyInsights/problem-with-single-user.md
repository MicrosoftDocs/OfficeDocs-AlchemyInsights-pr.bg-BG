---
title: Проблем с един потребител
ms.author: v-jmathew
author: v-jmathew
manager: scotv
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9004687"
- "8469"
ms.openlocfilehash: f3564063a3adf291ec4909ffeb2f6de0e478da96
ms.sourcegitcommit: f4ba304b92ed01e35273ecda67e9dc3ad9d475c1
ms.translationtype: MT
ms.contentlocale: bg-BG
ms.lasthandoff: 03/04/2021
ms.locfileid: "50429347"
---
# <a name="problem-with-single-user"></a>Проблем с един потребител

- Потребителят може да не е осигурен, защото услугата все още не е успяла да оцени потребителя. Прегледайте ръководството за продължителността на осигуряването, както и лентата за напредък на страницата за конфигуриране на обезпечаването. Ако стационарното състояние, зададено в секцията допълнителни данни, е преди датата, на която потребителят е бил създаден/актуализиран/изтрит, това означава, че все още не сме оценили потребителя. В този случай най-доброто нещо, което трябва да направите, е да изчакате услугата за осигуряване да завърши.

  - Имайте предвид, че нашата услуга е наясно само за промените в даден потребител в системата източник (ВП на облака). Трябва да има валидна промяна в системата източник за Azure AD за откриване на промяната и преливането й в Active Directory.
- Услугата за осигуряване е изчислила потребителя и е решила, че не трябва да бъде осигурена:
  - Ако сте задали филтър за обхват на обхвата на атрибута, уверете се, че потребителят отговаря на критериите, които сте задали.
  - Ако потребителите вече съществуват в целевата система и състоянието на потребителя в изходния и таргетния мач, няма да предприемем никакви последващи действия.
- Услугата за осигуряване се опитва да осигури на потребителя и е неуспешна. За тези сценарии Прегледайте раздела за отстраняване на неизправности и препоръки на регистрите за осигуряване:
  - Необходим атрибут на потребителя може да липсва в локалната Active Directory или Azure AD. Например правилата за създаване на userPrincipalName или sAMAccountName не генерират правилната стойност.
  - Атрибутът Match (обикновено employeeId) не се разрешава на уникален потребител в локален Active Directory или Azure AD. Например има два потребители с една и съща employeeId в AD и услугата връща код на грешка, за да се покаже дублирани записи за цел за един и същ запис източник.

За да прегледате регистрите за един потребител и групи, вижте [Преглед на осигуряването на регистрационни файлове за проблем с конкретен потребител](https://docs.microsoft.com/azure/active-directory/reports-monitoring/concept-provisioning-logs).