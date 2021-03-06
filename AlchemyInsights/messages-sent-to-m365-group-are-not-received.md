---
title: Microsoft 365 grupai nosūtītos ziņojumus nav saņēmuši visi dalībnieki
ms.author: pebaum
author: pebaum
manager: mnirkhe
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9003200"
- "5995"
ms.openlocfilehash: 080c060f5675065704c7209bd15e4cbb1236b8db
ms.sourcegitcommit: b71e5981b7f30ef2bce4e695118d03aa68a5be4a
ms.translationtype: HT
ms.contentlocale: lv-LV
ms.lasthandoff: 03/05/2021
ms.locfileid: "50480690"
---
# <a name="messages-sent-to-a-microsoft-365-group-are-not-received-by-all-members"></a>Microsoft 365 grupai nosūtītos ziņojumus nav saņēmuši visi dalībnieki

Nodrošiniet, ka visi grupas dalībnieki ir abonējuši e-pasta ziņojumu saņemšanu. Skatiet rakstu [Sekot grupai programmā Outlook](https://support.microsoft.com/office/e147fc19-f548-4cd2-834f-80c6235b7c36).  

Lai pārbaudītu to dalībnieku ziņojumu statusu, kuri ir abonējuši grupas e-pasta ziņojumus, [EXO PowerShell](https://docs.microsoft.com/powershell/exchange/connect-to-exchange-online-powershell?view=exchange-ps&preserve-view=true) palaidiet šādu komandu:

`Get-UnifiedGroup <GroupName> | Get-UnifiedGroupLinks -LinkType Subscribers`

Izmantojiet tālāk norādīto EXO PowerShell komandu, lai konfigurētu visus grupas dalībniekus Microsoft 365 grupai nosūtīto e-pasta ziņojumu saņemšanai viņu iesūtnē:

`$Group = "Address of [Microsoft 365 Groups]"Get-UnifiedGroupLinks $Group -LinkType Member | % {Add-UnifiedGroupLinks -Identity $Group -LinkType subscriber -Links $_.Guid.toString() -Confirm:$false}`

Piemēram:

`$Group = "testg@contoso.onmicrosoft.com"Get-UnifiedGroupLinks $Group -LinkType Member | % {Add-UnifiedGroupLinks -Identity $Group -LinkType subscriber -Links $_.Guid.toString() -Confirm:$false}`