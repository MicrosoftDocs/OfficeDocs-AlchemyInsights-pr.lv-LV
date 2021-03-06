---
title: e-datu atklāšanas eksportēšanas rīks
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "263"
- "928"
- "1100001"
- "3100022"
ms.assetid: b16d310d-1134-4959-be68-d1c0ad463930
ms.openlocfilehash: 67e59182a5053111a08f5fb2be814931a1aa815d
ms.sourcegitcommit: fbe6925797cab0b38172386f1b059dc122e452a4
ms.translationtype: MT
ms.contentlocale: lv-LV
ms.lasthandoff: 09/25/2020
ms.locfileid: "48277948"
---
# <a name="cant-install-or-run-the-ediscovery-export-tool"></a>Vai nevarat instalēt vai palaist e-datu atklāšanas eksportēšanas rīku?

Ja nevarat instalēt vai palaist e-datu atklāšanas eksportēšanas rīku, lai lejupielādētu meklēšanas rezultātus, skatiet tālāk minētos elementus.
  
- Jūsu izmantotais dators atbilst šiem priekšnosacījumiem:

  - 32 vai 64 bitu versijas Windows 7 un jaunākās versijās

  - Microsoft .NET Framework 4.7

  - Atbalstīta pārlūkprogramma:

  - Microsoft Edge

    Vai

  - Internet Explorer 10 un jaunākas versijas

    Citas pārlūkprogrammas, piemēram, Google Chrome un Mozilla Firefox, netiek atbalstītas.

- Jūsu organizācija var izveidot savienojumu ar Azure galapunktu, kas ir ** \* . BLOB.Core.Windows.NET** (aizstājējzīme apzīmē jūsu eksportēšanas darba unikālo identifikatoru).

- Jums ir piešķirta eksportēšanas loma Microsoft 365 drošības &amp; atbilstības centrā. Pēc noklusējuma šī loma ir piešķirta tikai e-datu atklāšanas pārvaldnieka lomu grupai. Skatiet rakstu [e-datu atklāšanas atļauju piešķiršana](https://docs.microsoft.com/microsoft-365/compliance/assign-ediscovery-permissions).

Papildinformāciju skatiet rakstā [satura meklēšanas rezultātu eksportēšana](https://docs.microsoft.com/microsoft-365/compliance/export-search-results).

Ja eksportējat vairāk nekā 100K pastkastes, ir jāizmanto tālāk norādītā PowerShell, lai lejupielādētu eksportēšanas rezultātus:  [Eksportējot rezultātus no vairāk nekā 100k pastkastēm](https://docs.microsoft.com/microsoft-365/compliance/export-search-results?view=o365-worldwide%23exporting-results-from-more-than-100000-mailboxes).