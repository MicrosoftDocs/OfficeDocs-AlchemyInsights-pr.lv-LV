---
title: Problēmas ar iekāpšanas mašīnas
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 07/14/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "6023"
- "9002913"
ms.openlocfilehash: 19b516dc21472e2c80a8b9046f802b329d15e4d6
ms.sourcegitcommit: 45c2aaeee58c0be466b76c7f0cd71e796d3c8f76
ms.translationtype: MT
ms.contentlocale: lv-LV
ms.lasthandoff: 07/15/2020
ms.locfileid: "45141653"
---
# <a name="issues-with-onboarding-machines"></a><span data-ttu-id="49d2f-102">Problēmas ar iekāpšanas mašīnas</span><span class="sxs-lookup"><span data-stu-id="49d2f-102">Issues with onboarding machines</span></span>

<span data-ttu-id="49d2f-103">Iespējams, ir problēmas ar iekāpšanas mašīnas MDATP pakalpojumu.</span><span class="sxs-lookup"><span data-stu-id="49d2f-103">You might have issues with onboarding machines to MDATP service.</span></span> <span data-ttu-id="49d2f-104">Ja varat piekļūt lietotāja datoram, rīkojieties šādi:</span><span class="sxs-lookup"><span data-stu-id="49d2f-104">If you can access the end-user machine, follow these steps:</span></span>

1. <span data-ttu-id="49d2f-105">Lejupielādējiet klienta [savienojamības analizatora](https://aka.ms/mdatpanalyzer) diagnostikas rīku.</span><span class="sxs-lookup"><span data-stu-id="49d2f-105">Download the [Client Connectivity Analyzer](https://aka.ms/mdatpanalyzer) diagnostic tool.</span></span>
2. <span data-ttu-id="49d2f-106">Ekstrakts un palaist MDATPAnalyzer.cmd.</span><span class="sxs-lookup"><span data-stu-id="49d2f-106">Extract and run MDATPAnalyzer.cmd.</span></span>
3. <span data-ttu-id="49d2f-107">Atrodiet diagnostikas žurnālu mapē ar nosaukumu MDATPClientAnalyzerResult, tajā pašā mapē, kurā tiek lejupielādēts rīks Analyzer.</span><span class="sxs-lookup"><span data-stu-id="49d2f-107">Locate the diagnostic log in the folder called MDATPClientAnalyzerResult, the same folder where the Analyzer tool is downloaded.</span></span>
4. <span data-ttu-id="49d2f-108">Pārskatiet žurnālfailu, MDATPClientAnalyzer.txt, lai atrastu savienojamības vai interneta starpniekservera iestatījumu problēmas.</span><span class="sxs-lookup"><span data-stu-id="49d2f-108">Review the log file, MDATPClientAnalyzer.txt, to find connectivity or internet proxy settings issues.</span></span>