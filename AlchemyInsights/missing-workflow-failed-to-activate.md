---
title: Липсващ работен поток не можа да се активира
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: e46ae8c5-3d81-457e-8c77-f7c1cbe267c4
ms.openlocfilehash: 604dc770c5c14ded6a8de1cec9e311b03b69f094
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: bg-BG
ms.lasthandoff: 09/14/2020
ms.locfileid: "47667075"
---
# <a name="missing-workflow-failed-to-activate"></a>Липсващ работен поток не можа да се активира

В колекция от сайтове на Microsoft SharePoint не можете да добавяте глобален многократно използваем работен поток (като например "одобрение-SharePoint 2010") към списък или библиотека.
  
За да отстраните този проблем, изпълнете следните стъпки: 
  
1. Отворете главния уеб сайт на колекцията от сайтове в SharePoint Designer 2013.
  
2. Под **обекти на сайт**изберете **работни потоци**. 
  
3. В **новата** секция на лентата на **работни потоци** изберете **повторно използваем работен поток**. 
  
4. В диалоговия прозорец **Създаване на повторно използваем работен поток** въведете името * * *Repair2010* * *. За **тип платформа**щракнете върху **работен поток на SharePoint 2010**, след което щракнете върху **OK**. 
  
1. В секцията **Запиши** на лентата на **работния поток** щракнете върху **публикуване**. 
  
2. В секцията **управление** на лентата на **работния поток** изберете **публикуване глобално**. В диалоговия прозорец за потвърждение, който се появява, изберете **OK**. 
  
3. В уеб браузър Намерете главния уеб сайт на колекцията от сайтове и след **това Получете** достъп до \> **функциите на колекцията**от сайтове. След това превключете функцията " **работни потоци** ": 
  
· Ако функцията е  *активирана* **, щракнете върху дезактивиране** и след това върху **Активирай**. 
  
· Ако функцията е  *дезактивирана*  , щракнете върху **Активирай**. 
  
За повече информация вижте [статията](https://go.microsoft.com/fwlink/?linkid=2047770&amp;clcid=0x409)по-долу.
  

