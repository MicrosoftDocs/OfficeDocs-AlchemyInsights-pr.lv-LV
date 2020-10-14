---
title: Microsoft 365 grupas e-pasta adreses maiņa
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "1200024"
- "4704"
ms.openlocfilehash: f54ca5df09d0604f6d58c6c8a41dc907485e1f04
ms.sourcegitcommit: beb9715ac0c8e8333fef6764ecd346b7401a2612
ms.translationtype: MT
ms.contentlocale: lv-LV
ms.lasthandoff: 10/10/2020
ms.locfileid: "48461944"
---
# <a name="change-email-address-of-a-microsoft-365-group"></a><span data-ttu-id="933a2-102">Microsoft 365 grupas e-pasta adreses maiņa</span><span class="sxs-lookup"><span data-stu-id="933a2-102">Change email address of a Microsoft 365 group</span></span>

<span data-ttu-id="933a2-103">Varat mainīt Microsoft 365 grupas e-pasta adresi, izmantojot administrēšanas centru.</span><span class="sxs-lookup"><span data-stu-id="933a2-103">You can change the email address of a Microsoft 365 group by using the admin center.</span></span> <span data-ttu-id="933a2-104">Vienkārši atlasiet grupu un atlasiet @edit e-pasta adresi.</span><span class="sxs-lookup"><span data-stu-id="933a2-104">Just select the group and select @edit email address.</span></span>

<span data-ttu-id="933a2-105">Varat arī izmantot komandu EXO PowerShell, lai mainītu Microsoft 365 grupas primāro SMTP adresi:</span><span class="sxs-lookup"><span data-stu-id="933a2-105">You can also use following the EXO PowerShell command to change the primary SMTP address of a Microsoft 365 group:</span></span>

`Set-UnifiedGroup <Group Name> -PrimarySmtpAddress <new SMTP Address>`

<span data-ttu-id="933a2-106">Piemēram</span><span class="sxs-lookup"><span data-stu-id="933a2-106">Example:</span></span>

`et-UnifiedGroup Marketing -PrimarySmtpAddress marketing@contoso.com`
