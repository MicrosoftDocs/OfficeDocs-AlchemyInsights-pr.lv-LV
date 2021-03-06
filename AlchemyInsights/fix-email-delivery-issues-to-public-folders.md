---
title: E-pasta piegādes problēmu novēršana uz pasta iespējotām publiskajām mapēm
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1956"
- "3500007"
ms.openlocfilehash: 74a26306766ed7952a3bbbcb06f1f0113a113024
ms.sourcegitcommit: 9fd002ce49ad9a7e58c3eb997a8063e2e1feab55
ms.translationtype: MT
ms.contentlocale: lv-LV
ms.lasthandoff: 10/06/2020
ms.locfileid: "48366471"
---
# <a name="fix-email-delivery-issues-to-mail-enabled-public-folders"></a>E-pasta piegādes problēmu novēršana uz pasta iespējotām publiskajām mapēm

Ja ārējie sūtītāji nevar nosūtīt ziņojumus uz jūsu e-pasta publiskajām mapēm, un sūtītāji saņem kļūdu: nav **atrasts (550 5.4.1)**, pārbaudiet, vai publiskas mapes e-pasta domēns ir konfigurēts kā iekšējs pārraides domēns, nevis autoritatīvs domēns:

1. Atveriet [Exchange admin Center (EAC)](https://docs.microsoft.com/Exchange/exchange-admin-center).

2. Dodieties uz sadaļu **pasta plūsmas** \> **akceptētie domēni**, atlasiet akceptēto domēnu un pēc tam noklikšķiniet uz **Rediģēt**.

3. Rekvizītu lapā, kas tiek atvērta, ja domēna tips ir iestatīts kā **autoritatīvs**, nomainiet vērtību uz **iekšējo releju** un pēc tam noklikšķiniet uz **Saglabāt**.

Ja ārējie sūtītāji saņem kļūdas ziņojumu, kam **nav atļaujas (550 5.7.13)**, izpildiet šo komandu pakalpojumā [Exchange Online PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell) , lai skatītu anonīmu lietotāju atļaujas publiskajā mapē:

`Get-PublicFolderClientPermission -Identity "<PublicFolderIdentity>" -User Anonymous` Piemēram, `Get-PublicFolderClientPermission -Identity "\Customer Discussion" -User Anonymous` .

Lai atļautu ārējiem lietotājiem nosūtīt e-pasta ziņojumus uz šo publisko mapi, pievienojiet CreateItems piekļuves tiesības lietotājam anonīms. Piemēram, `Add-PublicFolderClientPermission -Identity "\Customer Discussion" -User Anonymous -AccessRights CreateItems` .
