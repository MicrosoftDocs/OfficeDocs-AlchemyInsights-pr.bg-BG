---
title: Актуализиране на DNS записи да си сайт с настоящия си хостинг доставчик
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 5/2/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: 48251355-7383-4fdc-a1e1-9dc2c85a8d29
ms.openlocfilehash: a79302259e294ea5bf3b1d29393a412edb27a388
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: bg-BG
ms.lasthandoff: 01/24/2019
ms.locfileid: "29458246"
---
# <a name="update-dns-records-to-keep-your-website-with-your-current-hosting-provider"></a><span data-ttu-id="d94a6-102">Актуализиране на DNS записи да си сайт с настоящия си хостинг доставчик</span><span class="sxs-lookup"><span data-stu-id="d94a6-102">Update DNS records to keep your website with your current hosting provider</span></span>

1. <span data-ttu-id="d94a6-103">Страницата на [домейни](https://portal.office.com/adminportal/home#/Domains) изберете в списъка на домейни, домейн, което използвате за вашия уеб сайт и след това изберете **DNS настройките** в прозореца управление на.</span><span class="sxs-lookup"><span data-stu-id="d94a6-103">On the [Domains](https://portal.office.com/adminportal/home#/Domains) page, in the list of domains, select the domain you're using for your website, and then select **DNS settings** in the management pane.</span></span> 
    
2. <span data-ttu-id="d94a6-104">Изберете **+ нов потребителски запис** и въведете следното:</span><span class="sxs-lookup"><span data-stu-id="d94a6-104">Select **+ New custom record** and enter the following:</span></span> 
    
  - <span data-ttu-id="d94a6-105">За **DNS тип** въведете: **(адрес)**</span><span class="sxs-lookup"><span data-stu-id="d94a6-105">For **DNS type** enter: **A (Address)**</span></span>
    
  - <span data-ttu-id="d94a6-106">За **име на хост или псевдоним**въведете следното:**@**</span><span class="sxs-lookup"><span data-stu-id="d94a6-106">For **Host name or Alias**, type the following: **@**</span></span>
    
  - <span data-ttu-id="d94a6-107">За **IP адрес**въведете статичен IP адрес за вашия сайт, където той в момента е домакин (например 172.16.140.1).</span><span class="sxs-lookup"><span data-stu-id="d94a6-107">For **IP Address**, type the static IP address for your website where it's currently hosted (for example, 172.16.140.1).</span></span> 
    
    <span data-ttu-id="d94a6-p101">Това трябва да бъде *статичен* IP адрес на сайта, не *динамичен* IP адрес. Проверете сайта, където е домакин вашия сайт да се уверите, можете да получите на статичен IP адрес за вашия публичен уеб сайт.</span><span class="sxs-lookup"><span data-stu-id="d94a6-p101">This must be a  *static*  IP address for the website, not a  *dynamic*  IP address. Check with site where your website is hosted to make sure you can get a static IP address for your public website.</span></span> 
    
3. <span data-ttu-id="d94a6-110">Изберете **Запиши**.</span><span class="sxs-lookup"><span data-stu-id="d94a6-110">Select **Save**.</span></span> 
    
<span data-ttu-id="d94a6-111">В допълнение можете да създадете CNAME запис да помогне на клиентите намерите вашия уебсайт.</span><span class="sxs-lookup"><span data-stu-id="d94a6-111">In addition, you can create a CNAME record to help customers find your website.</span></span>
  
1. <span data-ttu-id="d94a6-112">Изберете **+ нов потребителски запис** и въведете следното:</span><span class="sxs-lookup"><span data-stu-id="d94a6-112">Select **+ New custom record** and enter the following:</span></span> 
    
  - <span data-ttu-id="d94a6-113">За **DNS тип** въведете: **CNAME (псевдоним)**</span><span class="sxs-lookup"><span data-stu-id="d94a6-113">For **DNS type** enter: **CNAME (Alias)**</span></span>
    
  - <span data-ttu-id="d94a6-114">За **име на хост или псевдоним**, въведете следното: **www**</span><span class="sxs-lookup"><span data-stu-id="d94a6-114">For **Host name or Alias**, type the following: **www**</span></span>
    
  - <span data-ttu-id="d94a6-115">За **пункта до адрес**въведете пълното домейн име (FQDN) за вашия уеб сайт (например contoso.com).</span><span class="sxs-lookup"><span data-stu-id="d94a6-115">For **Points to address**, type the fully qualified domain name (FQDN) for your website (for example, contoso.com).</span></span> 
    
2. <span data-ttu-id="d94a6-116">Изберете **Запиши**.</span><span class="sxs-lookup"><span data-stu-id="d94a6-116">Select **Save**.</span></span> 
    

