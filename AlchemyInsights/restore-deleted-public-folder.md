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
# <a name="restore-a-deleted-public-folder"></a><span data-ttu-id="1c071-102">Izdzēstas publiskās mapes atjaunošana</span><span class="sxs-lookup"><span data-stu-id="1c071-102">Restore a deleted public folder</span></span>

<span data-ttu-id="1c071-103">**Lai no publiskās mapes atjaunotu izdzēstos vienumus**:</span><span class="sxs-lookup"><span data-stu-id="1c071-103">**To restore deleted items from a public folder**:</span></span>

- <span data-ttu-id="1c071-104">Skatiet [nevar atkopt izdzēstos vienumus no e-pasta publiskās mapes programmā Outlook 2016](https://aka.ms/pfrec).</span><span class="sxs-lookup"><span data-stu-id="1c071-104">See [You can't recover deleted items from a non-mail public folder in Outlook 2016](https://aka.ms/pfrec).</span></span>
 
<span data-ttu-id="1c071-105">**Lai atjaunotu dzēstu publisko mapi (jebkura veida)**:</span><span class="sxs-lookup"><span data-stu-id="1c071-105">**To restore a deleted public folder (of any type)**:</span></span> 

- <span data-ttu-id="1c071-106">Lūdzu, izmantojiet šādu komandu EXO PowerShell:</span><span class="sxs-lookup"><span data-stu-id="1c071-106">Please use following EXO PowerShell command:</span></span>

    <span data-ttu-id="1c071-107">Sintakse:</span><span class="sxs-lookup"><span data-stu-id="1c071-107">Syntax:</span></span>

    ><span data-ttu-id="1c071-108">$pf = get-PublicFolder \ NON_IPM_SUBTREE \ DUMPSTER_ROOT-Recurse |? {$_. Nosaukums-EQ "\<name_of_deleted_public_Folder"}; Set-PublicFolder $pf. identitātes ceļa \<ceļš, kur tiks atjaunota mape></span><span class="sxs-lookup"><span data-stu-id="1c071-108">$pf=Get-PublicFolder \NON_IPM_SUBTREE\DUMPSTER_ROOT -Recurse  | ?{$_.Name -eq "\<name_of_deleted_public_Folder"};Set-PublicFolder $pf.identity -Path \<path where the folder will be restored></span></span>

    <span data-ttu-id="1c071-109">Piemērs: šī komanda atjaunos Subfolder1 un novietot to zem \Parent1:</span><span class="sxs-lookup"><span data-stu-id="1c071-109">Example: The following command will restore Subfolder1 and place it under \Parent1:</span></span>

    ><span data-ttu-id="1c071-110">$pf = get-PublicFolder \ NON_IPM_SUBTREE \ DUMPSTER_ROOT-Recurse |? {$_. Nosaukums-EQ "Subfolder1"}; Kopa PublicFolder $pf. identitātes ceļš \ parent1</span><span class="sxs-lookup"><span data-stu-id="1c071-110">$pf=Get-PublicFolder \NON_IPM_SUBTREE\DUMPSTER_ROOT -Recurse | ?{$_.Name -eq "Subfolder1"};Set-PublicFolder $pf.identity -Path \Parent1</span></span>

<span data-ttu-id="1c071-111">Plašāku informāciju skatiet sadaļā [izdzēstas publiskās mapes atjaunošana](https://docs.microsoft.com/exchange/collaboration-exo/public-folders/restore-deleted-public-folder) .</span><span class="sxs-lookup"><span data-stu-id="1c071-111">See [Restore a deleted public folder](https://docs.microsoft.com/exchange/collaboration-exo/public-folders/restore-deleted-public-folder) for more details.</span></span>
