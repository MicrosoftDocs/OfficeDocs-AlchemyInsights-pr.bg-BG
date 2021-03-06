---
title: 2491 известия за имейл съобщения от правилата за "phisher, доставени поради клиент или за заместване на потребители"
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 2491
ms.assetid: ''
ms.openlocfilehash: 5b5faa08542cb5878107f10afb34427f636562ac
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: bg-BG
ms.lasthandoff: 09/14/2020
ms.locfileid: "47728600"
---
# <a name="alert-email-messages-from-the-phish-delivered-due-to-tenant-or-user-override-policy"></a>Информиране на имейл съобщения от правилата на "phisher доставяния поради клиент или за отмяна на потребители"

За клиенти с Office 365 ATP P1 и P2 се предоставят правила за известия по подразбиране с име "уеб клиент или превключвател за потребители". Ако сте получили това известие, ето стъпките, за да изследвате:

1. От уведомителното съобщение щракнете върху **Преглед на известяване** , за да отидете на страницата за **предупреждения** в центъра за съответствие на & за защита.

2. Изберете известието, за да видите опцията за **Преглед на списъка със съобщения** или да **преглеждате съобщения в Explorer**. И двете опции ще ви отведат до подробностите за съобщението, което включва ИД на съобщението. Имайте предвид, че връзката за Explorer на заплахите автоматично ще филтрира съобщенията, които отговарят на критериите за уведомяване. Може да се наложи да настроите филтъра за дата в Explorer на заплахите.

Фишинг съобщението е доставено поради ръчно конфигурирани замествания:

- Позволен подател или домейн, зададен от потребителя.

- Позволен подател или домейн, зададено от администратора в правила за нежелана поща.

- Позволен IP адрес в правилата за филтриране на връзката.

- Правило за поток на поща (известно също като транспортно правило), което е конфигурирано да позволява съобщения в.

Ако смятате, че съобщението е било неправилно маркирано като Фиш, използвайте [добавката за съобщение на отчета](https://support.office.com/article/b5caa9f1-cdf3-4443-af8c-ff724ea719d2) за Outlook, за да подадете образци на съобщения на Microsoft.
