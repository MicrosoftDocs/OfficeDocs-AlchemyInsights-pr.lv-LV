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
# <a name="issues-with-onboarding-machines"></a>Problēmas ar iekāpšanas mašīnas

Iespējams, ir problēmas ar iekāpšanas mašīnas MDATP pakalpojumu. Ja varat piekļūt lietotāja datoram, rīkojieties šādi:

1. Lejupielādējiet klienta [savienojamības analizatora](https://aka.ms/mdatpanalyzer) diagnostikas rīku.
2. Ekstrakts un palaist MDATPAnalyzer.cmd.
3. Atrodiet diagnostikas žurnālu mapē ar nosaukumu MDATPClientAnalyzerResult, tajā pašā mapē, kurā tiek lejupielādēts rīks Analyzer.
4. Pārskatiet žurnālfailu, MDATPClientAnalyzer.txt, lai atrastu savienojamības vai interneta starpniekservera iestatījumu problēmas.