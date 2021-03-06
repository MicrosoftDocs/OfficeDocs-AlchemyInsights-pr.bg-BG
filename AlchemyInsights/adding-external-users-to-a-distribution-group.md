---
title: Добавяне на външни потребители към група за разпространение
ms.author: chrisda
author: chrisda
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: caa0f310-0bb7-48e3-8ad2-cb358b53bbba
ms.openlocfilehash: 03cfd2c576cb03cbefd524a4ab6f04e2ef1eebec
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: bg-BG
ms.lasthandoff: 09/14/2020
ms.locfileid: "47663502"
---
# <a name="add-external-users-to-a-distribution-group"></a>Добавяне на външни потребители към група за разпространение

Добавянето на външен контакт към група за разпространение е процес от две стъпки:
  
1. Създаване на контакт за поща за външни потребители:
    
    1. В центъра за администриране отидете на страницата с **Users**  >  [Контакти](https://admin.microsoft.com/adminportal/home#/Contact) на потребителите. 
    
    2. Изберете **Добавяне на контакт**.
    
    3. Въведете информацията за вашия контакт и изберете **Добави**.
    
2. Добавете контакта за поща към вашата ГД:
    
    1. В центъра за администриране отидете на страницата **Groups**  >  [Groups](https://admin.microsoft.com/adminportal/home#/groups) . 
    
    2. Намерете Генералната дирекция, към която искате да добавите външния потребител, и я изберете, за да отворите диалоговия прозорец "Редактиране".
    
    3. В раздела **членове** изберете **Преглед на всички и управление на членовете**. 
    
    4. Изберете **Добавяне на членове**.
    
    5. Изберете контакта за поща, който създадохте в предишната стъпка, и след това изберете **Запиши**.
    
Ако след като изпълните тези стъпки, външните потребители не могат да изпращат имейли до ГД или да не получават имейли от нея, може да се окаже, че Генералната дирекция е маркирана да позволява имейли само от вътрешни потребители. Можете да проверите тази конфигурация и да я коригирате, като следвате инструкциите [тук](https://docs.microsoft.com/exchange/mail-flow-best-practices/non-delivery-reports-in-exchange-online/fix-error-code-5-7-133-in-exchange-online).
  
 **Забележка:** Тези инструкции не важат, ако типът на групата ви е "Microsoft 365 Group" вместо "група за разпространение". Ако това е така, можете да добавите външния потребител директно към групата от Outlook. Подробна информация за гостите на Microsoft 365 Groups, както и инструкции за добавяне на външни гости, могат да бъдат намерени в [тази статия](https://support.office.com/article/Guest-access-in-Office-365-Groups-bfc7a840-868f-4fd6-a390-f347bf51aff6.aspx).
  