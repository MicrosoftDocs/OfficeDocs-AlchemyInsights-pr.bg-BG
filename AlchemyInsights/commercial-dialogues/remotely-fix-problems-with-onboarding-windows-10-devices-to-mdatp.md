---
title: Отдалечено отстраняване на проблеми при внедряване на устройства с Windows 10 за защита от защитата на Microsoft Defender
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
- "9000760"
- "7391"
ms.openlocfilehash: 5473d090f6d4680f9a62f34f943ac6cea53b2079
ms.sourcegitcommit: 6312ee31561db36104f32282d019d069ede69174
ms.translationtype: MT
ms.contentlocale: bg-BG
ms.lasthandoff: 03/11/2021
ms.locfileid: "50743781"
---
# <a name="remotely-fix-problems-with-onboarding-windows-10-devices-to-microsoft-defender-advanced-threat-protection"></a><span data-ttu-id="98d97-102">Отдалечено отстраняване на проблеми при внедряване на устройства с Windows 10 за защита от защитата на Microsoft Defender</span><span class="sxs-lookup"><span data-stu-id="98d97-102">Remotely fix problems with onboarding Windows 10 devices to Microsoft Defender Advanced Threat Protection</span></span>

<span data-ttu-id="98d97-103">Ако имате достъп до отдалечения компютър, изпълнете следните стъпки:</span><span class="sxs-lookup"><span data-stu-id="98d97-103">If you can access the remote computer, follow these steps:</span></span>

1. <span data-ttu-id="98d97-104">Изтеглете диагностичния инструмент за [анализатор на свързването на клиенти](https://go.microsoft.com/fwlink/?linkid=2143466) .</span><span class="sxs-lookup"><span data-stu-id="98d97-104">Download the [Client Connectivity Analyzer](https://go.microsoft.com/fwlink/?linkid=2143466) diagnostic tool.</span></span>
2. <span data-ttu-id="98d97-105">Extract и Run MDATPAnalyzer. cmd.</span><span class="sxs-lookup"><span data-stu-id="98d97-105">Extract and run MDATPAnalyzer.cmd.</span></span>
3. <span data-ttu-id="98d97-106">Намерете диагностичния регистрационен файл в папката MDATPClientAnalyzerResult, която е същата папка, в която е изтеглен инструментът Analyzer.</span><span class="sxs-lookup"><span data-stu-id="98d97-106">Locate the diagnostic log in the MDATPClientAnalyzerResult folder, which is the same folder where the Analyzer tool was downloaded.</span></span>
4. <span data-ttu-id="98d97-107">За да намерите проблеми с настройките за свързване или интернет прокси сървъра, Прегледайте регистрационния файл MDATPClientAnalyzer.txt.</span><span class="sxs-lookup"><span data-stu-id="98d97-107">To find issues with connectivity or Internet proxy settings, review the log file MDATPClientAnalyzer.txt.</span></span>

<span data-ttu-id="98d97-108">За да научите повече, вижте [проблеми с вградените машини](https://go.microsoft.com/fwlink/?linkid=2143634).</span><span class="sxs-lookup"><span data-stu-id="98d97-108">To learn more, see [Issues with onboarding machines](https://go.microsoft.com/fwlink/?linkid=2143634).</span></span>