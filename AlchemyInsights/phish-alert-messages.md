---
title: 2491 brīdinājuma e-pasta ziņojumi no adresi phish, kas tiek piegādāta nomnieka vai lietotāja ignorēšanas politikā
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 2491
ms.assetid: ''
ms.openlocfilehash: 5b5faa08542cb5878107f10afb34427f636562ac
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: lv-LV
ms.lasthandoff: 09/14/2020
ms.locfileid: "47728618"
---
# <a name="alert-email-messages-from-the-phish-delivered-due-to-tenant-or-user-override-policy"></a>Brīdinājums par e-pasta ziņojumu saņemšanu no nomnieka vai lietotāja ignorēšanas adresi phish

Noklusējuma brīdinājumu politika "adresi phish, kas tiek piegādāta nomnieka vai lietotāja ignorēšanai", ir izlabota nomniekiem ar Office 365 ATP P1 un P2 licencēm. Ja saņēmāt šo brīdinājumu, ir jāveic tālāk norādītās darbības.

1. Brīdinājuma ziņojumā noklikšķiniet uz **Skatīt brīdinājumu** , lai atvērtu **brīdinājumu** lapu drošības & atbilstības centrā.

2. Atlasiet brīdinājumu, lai skatītu **ziņojumu saraksta** vai skata ziņojumu skatīšanas opciju **programmā Explorer**. Abas šīs opcijas sniedz detalizētu informāciju par ziņojumu, kas ietver ziņojuma ID. Ņemiet vērā, ka draudi Explorer saite automātiski filtrēs ziņojumus, kas atbildīs brīdinājuma kritērijiem. Iespējams, ka ir jāpielāgo datuma filtrs draudu pētniekā.

Pikšķerēšanas ziņojums tika piegādāts, jo ir manuāli konfigurēta ignorēšana:

- Lietotājam iestatīts atļautais sūtītājs vai domēns.

- Atļautais sūtītājs vai domēns, ko iestatījis administrators surogātpasta novēršanas politikā.

- Atļauto IP adresi savienojuma filtra politikā.

- Pasta plūsmas kārtula (tiek dēvēta arī par transporta kārtulu), kas ir konfigurēta, lai atļautu saņemt ziņojumus.

Ja uzskatāt, ka ziņojums ir nepareizi atzīmēts kā adresi phish, izmantojiet Outlook [atskaišu ziņojumu pievienojumprogrammu](https://support.office.com/article/b5caa9f1-cdf3-4443-af8c-ff724ea719d2) , lai iesniegtu ziņojumu paraugus Microsoft.
