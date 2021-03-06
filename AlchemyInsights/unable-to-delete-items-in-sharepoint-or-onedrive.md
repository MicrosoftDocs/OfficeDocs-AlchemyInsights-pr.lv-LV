---
title: Nevar izdzēst vienumus pakalpojumā SharePoint vai OneDrive
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1851"
- "2377"
- "9000255"
ms.assetid: ''
ms.openlocfilehash: db45aa8df40484fdcda7c430f1ca27482a1dd4ce
ms.sourcegitcommit: a9415f3ae8c7ba267b5134bcbdc1e070cea41a0f
ms.translationtype: MT
ms.contentlocale: lv-LV
ms.lasthandoff: 11/12/2020
ms.locfileid: "49019590"
---
# <a name="unable-to-delete-items"></a>Nevar izdzēst vienumus

- Saglabāšanas politikas var izraisīt šo problēmu, ir jāatspējo vai jāizslēdz attiecīgais aizturēšanas iemesls. Kad saglabāšanas politika vai aizturēt ir noņemta, var paiet līdz pat 24 stundām, līdz izmaiņas stāsies spēkā. Pārliecinieties, vai vienumā nav [saglabāšanas politikas](https://docs.microsoft.com/microsoft-365/compliance/retention-policies) iestatījumu.

- Vietne, iespējams, ir pārsniedzis krātuves ierobežojumu, palielina [vietnes kvotu](https://docs.microsoft.com/powershell/module/sharepoint-online/set-sposite?view=sharepoint-ps) un izdzēš vienumu.

- Pārliecinieties, vai vienums nav [paņemts](https://support.office.com/article/check-out-check-in-or-discard-changes-to-files-in-a-library-7e2c12a9-a874-4393-9511-1378a700f6de) citam lietotājam.

- Visbeidzot administratori var izmantot [SharePoint modeļus un prakses](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps#installation) (PnP), kas satur PowerShell komandu bibliotēku, kas sniedz iespēju veikt sarežģītas pārvaldības darbības, piemēram, likt dzēst spītīgus vienumus.
- [PNP faila noņemšana](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfile?view=sharepoint-ps)
- [PNP mapes noņemšana](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfolder?view=sharepoint-ps)
- [PNP saraksta vienuma noņemšana](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnplistitem?view=sharepoint-ps)
- [PNP saraksta noņemšana](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnplist?view=sharepoint-ps)
- [PNP lauka noņemšana (kolonna)](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfield?view=sharepoint-ps)