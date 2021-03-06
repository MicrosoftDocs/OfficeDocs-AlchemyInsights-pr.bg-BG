---
title: Настройване на списъка с устройства
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 07/27/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "1281"
- "6700008"
ms.openlocfilehash: 5d2be7485be8578f7fdee3216dc6f3970be67fd1
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: bg-BG
ms.lasthandoff: 09/14/2020
ms.locfileid: "47667867"
---
# <a name="intune-device-inventory"></a>Настройване на списъка с устройства

Blade на устройства предоставя на администратора вникване в устройства под управление в съзвучие на база на устройство. Показаната информация включва: хардуер, открити приложения, състояние на съответствие на устройството и състояние на конфигурацията на устройството.

Данни за инвентаризация за хардуер и открити приложения се събират в седемдневен цикъл. Приложенията и определени елементи на хардуера се различават в зависимост от операционната система на устройството и дали устройството е лично или корпоративна собственост.

За повече информация вижте [Вижте подробности за устройството в настройки](https://docs.microsoft.com/intune/device-inventory).

**ЧЗВ**

В: не получавам пълен списък с налични приложения за приложенията, които са записани на устройства с Windows. Защо не?

А: към този момент само съвременните приложения са изброени за компютри с Windows 10, които се идентифицират като корпоративни устройства. В "Настройки" не се събира информация за Win32 приложенията, инсталирани на тези устройства.

В: защо телефонните номера не се събират от всички устройства?

А: телефони, категоризирани като корпоративни устройства в "ненастрои", не се идентифицират с пълния си телефонен номер, когато например стартирате отчет за инвентаризация на мобилно устройство. Телефонните номера за собствено устройство винаги се маскират частично със звездички (* * * *) и показват само последните четири цифри.