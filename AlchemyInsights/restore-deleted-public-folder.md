---
title: Izdzēstas publiskās mapes atjaunošana
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3500007"
- "3488"
ms.openlocfilehash: 7b04612daca61650d162c1dde240e25c1b185b04
ms.sourcegitcommit: 8ba12eff67e405f5922ea4cc35155e3036447859
ms.translationtype: MT
ms.contentlocale: lv-LV
ms.lasthandoff: 02/15/2020
ms.locfileid: "42063694"
---
# <a name="restore-a-deleted-public-folder"></a>Izdzēstas publiskās mapes atjaunošana

**Lai no publiskās mapes atjaunotu izdzēstos vienumus**:

- Skatiet [nevar atkopt izdzēstos vienumus no e-pasta publiskās mapes programmā Outlook 2016](https://aka.ms/pfrec).
 
**Lai atjaunotu dzēstu publisko mapi (jebkura veida)**: 

- Lūdzu, izmantojiet šādu komandu EXO PowerShell:

    Sintakse:

    >$pf = get-PublicFolder \ NON_IPM_SUBTREE \ DUMPSTER_ROOT-Recurse |? {$_. Nosaukums-EQ "\<name_of_deleted_public_Folder"}; Set-PublicFolder $pf. identitātes ceļa \<ceļš, kur tiks atjaunota mape>

    Piemērs: šī komanda atjaunos Subfolder1 un novietot to zem \Parent1:

    >$pf = get-PublicFolder \ NON_IPM_SUBTREE \ DUMPSTER_ROOT-Recurse |? {$_. Nosaukums-EQ "Subfolder1"}; Kopa PublicFolder $pf. identitātes ceļš \ parent1

Plašāku informāciju skatiet sadaļā [izdzēstas publiskās mapes atjaunošana](https://docs.microsoft.com/exchange/collaboration-exo/public-folders/restore-deleted-public-folder) .
