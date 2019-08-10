---
title: Apmainiet savu klasisko saknes vietni ar mūsdienu vietā
ms.author: efrene
author: efrene
ms.date: 8/6/2019
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.assetid: ''
ms.custom:
- "9000687"
- "2579"
ms.openlocfilehash: 0f6f962314d9099bd21c281a23ad2e95742da4a8
ms.sourcegitcommit: 631e527967f4d641bc9227642ffe38967ae87a00
ms.translationtype: MT
ms.contentlocale: lv-LV
ms.lasthandoff: 08/09/2019
ms.locfileid: "36270751"
---
# <a name="swap-your-classic-root-site-with-a-modern-site"></a>Apmainiet savu klasisko saknes vietni ar mūsdienu vietā

Vidē bija uzslieta aprīlī 2019, saknes vietni mūsdienu vietu var mainīt, izmantojot Microsoft PowerShell:

- Ja lietojat citu vietni, kuru vēlaties izmantot kā saknes vietni, (mijmaiņas) saknes vietni var aizstāt ar to. 
    - Izmantot [Izsaukums SPSiteSwap](https://docs.microsoft.com/powershell/module/sharepoint-online/invoke-spositeswap?view=sharepoint-ps) swap atrašanās vietu ar citu vietā vienlaikus arhivē sākotnējā vietā. Pieejama gan darba grupas vietni (nav pievienots grupai) un saziņas vietne. 

- Tiks ieviesti papildu iespējas drīz, kas ļaus jums paturēt lietojot satura vietnē, bet pārvērst esošo vietni ir saziņas vietne. 
>[!Important]
>Šīs iespējas tiek izveltnē pakāpeniski. Turpina pārbaudīt atjauninājumus Office 365 ziņu centru. 

## <a name="known-issues-with-swapping-sites"></a>Zināmas problēmas ar apmainīšana vietām

- Mērķa vietnes var atgriezt "nav atrasts" kļūda (HTTP 404) uz neilgu laika periodu.
- Saturs būs nepieciešams recrawled atjaunināt meklēšanas indeksā. Nav nepieciešama manuāla soļu - tas tiks veikts automātiski.
- Viss atkarīgs no "statisku" saites (piemēram, failu sinhronizēšana un OneNote failus) vajadzēs manuāli jālabo.
- Ja avota vietnes organizatoriskie jaunumi vietā, atjaunināt URL.Parādīts saraksts ar visu organizatorisko ziņu portālos.
- Project Server vietņu, iespējams, tiks pārbaudīti, vai tie ir joprojām saistīts pareizi.




