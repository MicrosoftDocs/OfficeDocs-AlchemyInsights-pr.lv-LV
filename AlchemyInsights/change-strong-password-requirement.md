---
title: Drošas paroles prasības mainīšana
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
- "9000105"
- "1600"
ms.openlocfilehash: 8ce331275e066b5a4f177ae27178ec726f90762f
ms.sourcegitcommit: aa35d2e1829f7d07f64fb891bf73b1fd80f0864c
ms.translationtype: MT
ms.contentlocale: lv-LV
ms.lasthandoff: 10/30/2020
ms.locfileid: "48804430"
---
# <a name="change-strong-password-requirement"></a>Drošas paroles prasības mainīšana

Pēc noklusējuma Microsoft pieprasa stipras paroles.

Izmantojot PowerShell, varat atspējot stipras paroles konkrētiem lietotājiem, izmantojot šīs komandas:

`Set-MsolUser –UserPrincipalName <UserPrincipalName> –StrongPasswordRequired  $false`

Lai atspējotu stipras paroles visiem lietotājiem, izmantojiet:

`Get-MsolUser | Set-MsolUser -StrongPasswordRequired $false`

- [Papildinformācija par paroļu politiku](https://docs.microsoft.com/azure/active-directory/authentication/concept-sspr-policy#password-policies-that-only-apply-to-cloud-user-accounts)
- [Kā izveidot savienojumu ar Microsoft 365, izmantojot PowerShell](https://docs.microsoft.com/office365/enterprise/powershell/connect-to-office-365-powershell#connect-with-the-microsoft-azure-active-directory-module-for-windows-powershell)
- [Plašāka informācija par PowerShell MsolUser komandām](https://docs.microsoft.com/powershell/module/msonline/set-msoluser?view=azureadps-1.0)
