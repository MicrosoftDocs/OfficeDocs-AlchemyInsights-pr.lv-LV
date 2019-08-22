---
title: Pārmaiņas stipras paroles prasība
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000105"
- "1600"
ms.openlocfilehash: f8790a26ec7c5de57f5dbfc9e1c162767c599f03
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: lv-LV
ms.lasthandoff: 08/22/2019
ms.locfileid: "36518766"
---
# <a name="change-strong-password-requirement"></a>Pārmaiņas stipras paroles prasība

Korporācija Microsoft pieprasa stiprās paroles pēc noklusējuma. 

Izmantojot programmu PowerShell, varat atspējot stipras paroles atsevišķiem lietotājiem ar šo komandu:<br>
*Kopa MsolUser-UserPrincipalName <UserPrincipalName> -StrongPasswordRequired $false*

- [Plašāku informāciju par paroļu politika](https://docs.microsoft.com/azure/active-directory/authentication/concept-sspr-policy#password-policies-that-only-apply-to-cloud-user-accounts)
- [Kā izveidot savienojumu ar biroja 365 izmantojot PowerShell](https://docs.microsoft.com/office365/enterprise/powershell/connect-to-office-365-powershell#connect-with-the-microsoft-azure-active-directory-module-for-windows-powershell)
- [Informacijos apie PowerShell MsolUser komandas](https://docs.microsoft.com/powershell/module/msonline/set-msoluser?view=azureadps-1.0)