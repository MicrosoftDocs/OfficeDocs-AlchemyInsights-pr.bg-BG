---
title: Откриване на сайт
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 03/08/2021
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9143"
- "9005291"
ms.openlocfilehash: bdf94220de45d92f63e56501ea4e35389224d25c
ms.sourcegitcommit: 475a9eaa095812091991857df6cf6490a8bbe179
ms.translationtype: MT
ms.contentlocale: bg-BG
ms.lasthandoff: 03/08/2021
ms.locfileid: "50692533"
---
# <a name="do-site-discovery"></a>Откриване на сайт

Ако вашата организация все още използва стари уеб приложения и планира да използва режима на Internet Explorer (което повечето клиенти имат), трябва да направите допълнително откриване на сайта.

**Вече сте разположили по-стара версия на Microsoft Edge**

Ако вече сте конфигурирали вашия списък с корпоративен сайт за работа с наследени версии на Microsoft Edge, откриването на сайта е почти готово. Едно нещо, което може да се наложи да направите, е да добавите неутрални сайтове.

Неутралните сайтове обикновено са сайтовете, които предоставят еднократна идентификация (SSO). Ако отидете в неутрален сайт от Microsoft Edge, след което искате да останете в Microsoft Edge за удостоверяване. Ако отидете в неутрален сайт в режим на Internet Explorer, трябва да останете в режима на Internet Explorer, за да удостоверите самоличността си.

Можете да идентифицирате всеки див или друг неутрален сайт, който използвате, и да ги добавите към вашия списък с корпоративни сайтове.

**Internet Explorer е вашият браузър по подразбиране**

Ако използвате само Internet Explorer сега, е възможно да не знаете кои сайтове са надстроени до съвременните уеб стандарти и което все още изисква Internet Explorer. Ще искате да търсите и да добавяте тези сайтове към списъка с корпоративни сайтове, така че да можете да използвате режима на Internet Explorer само за тези сайтове.

> [!NOTE]
> [Откритието Enterprise Site](https://docs.microsoft.com/internet-explorer/ie11-deploy-guide/collect-data-using-enterprise-site-discovery) открива сайтовете, които може да са необходими за режима на Internet Explorer. В Windows 10, Windows 8,1 или Windows 7 можете да събирате данни на компютри, на които се изпълнява Windows Internet Explorer 8 чрез Internet Explorer 11.

**Анализиране на данни**

След като съберете данни за сайта, ви препоръчваме следния процес от четири стъпки за анализиране на данните:
1. Сортирайте данните по домейн и след това чрез URL адрес.
2. Определете границите на дадено приложение, за да конфигурирате за режим на Internet Explorer. Искате да включите всички сайтове и уеб контроли, които определят приложението, но не искате да включвате допълнителни сайтове и контроли. Някои сайтове може да са толкова прости, *https://contoso.com/app1* докато други може да изискват от вас да дефинирате множество сайтове и страници.
3. Изпробвайте приложението, за да се уверите, че не работи по този език. Много сайтове ще ви предложат модерно съдържание, когато откриват модерен браузър и предлагат само наследени съдържание, когато откриват Internet Explorer.
4. Добавете приложението към вашия списък с корпоративен сайт, ако то не е изпробвано.

> [!NOTE]
> Като най-добра практика групирайте всички сайтове, които съдържат приложение. По този начин, когато надстроите приложение, е по-лесно да премахнете целия сайт от режим на Internet Explorer и да започнете да използвате модерен браузър за това приложение.

Когато сте готови с откриването на сайта и сте анализирали данните, сте готови да започнете да преглеждате стратегията си за канала.

