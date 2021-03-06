---
title: Lietotāja piekrišanas problēmu novēršana
ms.author: v-aiyengar
author: AshaIyengar21
manager: dansimp
ms.date: 01/18/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9004353"
- "7785"
ms.openlocfilehash: 7249bafe1b047c66d9351a79f1782cfcc1a936a1
ms.sourcegitcommit: 7b213fd5e8a3fdb5c602673dc194d576d372ac96
ms.translationtype: MT
ms.contentlocale: lv-LV
ms.lasthandoff: 01/18/2021
ms.locfileid: "49901188"
---
# <a name="troubleshoot-user-consent"></a>Lietotāja piekrišanas problēmu novēršana

1. Varat konfigurēt, kā lietotāji piekrīt lietojumprogrammām, izmantojot Azure portālu vai PowerShell. Papildinformāciju skatiet sadaļā [lietotāju atļauju iestatījumi](https://docs.microsoft.com/azure/active-directory/manage-apps/configure-user-consent?tabs=azure-portal#user-consent-settings) .
1. Administrators var izmantot arī [Microsoft GRAPH API](https://docs.microsoft.com/azure/active-directory/manage-apps/configure-user-consent?tabs=azure-portal#user-consent-settings) , lai piešķirtu piekrišanu pilnvarotām atļaujām viena lietotāja vārdā. Lai iegūtu papildinformāciju, skatiet rakstu [piekļuves iegūšana lietotāja vārdā](https://docs.microsoft.com/graph/auth-v2-user).
1. [Lietotāja piekrišanas kļūdas](https://docs.microsoft.com/azure/active-directory/manage-apps/application-sign-in-unexpected-user-consent-error): šajā rakstā ir aplūkotas kļūdas, kas var rasties, ja piekrītat lietojumprogrammai. Ja esat problēmu novēršana saistībā ar negaidītu piekrišanu, kas nesatur nevienu kļūdu ziņojumu, skatiet sadaļu [AZURE ad autentifikācijas scenāriji](https://docs.microsoft.com/azure/active-directory/manage-apps/application-sign-in-unexpected-user-consent-error).