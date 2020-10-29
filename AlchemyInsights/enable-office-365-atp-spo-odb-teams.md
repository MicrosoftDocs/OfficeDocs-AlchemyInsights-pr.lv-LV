---
title: Iespējojiet Office 365 ATP pakalpojumam SharePoint, OneDrive un Microsoft Teams
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Admin_O365
ms.custom: 3100021
ms.openlocfilehash: bef43656097c6f27677172899df1ada7900a9b64
ms.sourcegitcommit: 4caf5e6c2fee2903ccaf92cfc9006eb580faa7ba
ms.translationtype: MT
ms.contentlocale: lv-LV
ms.lasthandoff: 10/29/2020
ms.locfileid: "48801058"
---
# <a name="enable-microsoft-defender-for-office-365-for-sharepoint-online-onedrive-and-microsoft-teams"></a><span data-ttu-id="5548a-102">Iespējot Microsoft Defender pakalpojumam Office 365 pakalpojumam SharePoint Online, OneDrive un Microsoft Teams</span><span class="sxs-lookup"><span data-stu-id="5548a-102">Enable Microsoft Defender for Office 365 for SharePoint Online, OneDrive, and Microsoft Teams</span></span>

1. <span data-ttu-id="5548a-103">Dodieties uz https://protection.office.com un pierakstieties.</span><span class="sxs-lookup"><span data-stu-id="5548a-103">Go to https://protection.office.com and sign in.</span></span>
2. <span data-ttu-id="5548a-104">Izvēlieties **draudus pārvaldības**  >  **politikas**  >  **drošības pielikumi** .</span><span class="sxs-lookup"><span data-stu-id="5548a-104">Choose **Threat management** > **Policy** > **Safe Attachments** .</span></span>
3. <span data-ttu-id="5548a-105">Atlasiet **Ieslēgt ATP pakalpojumam SharePoint, OneDrive un Microsoft Teams** un pēc tam noklikšķiniet uz **Saglabāt** .</span><span class="sxs-lookup"><span data-stu-id="5548a-105">Select **Turn on ATP for SharePoint, OneDrive, and Microsoft Teams** , and then click **Save** .</span></span>
4. <span data-ttu-id="5548a-106">Ieteicams Kā globālais administrators vai SharePoint Online administrators izpildiet [Set-SPOTenant](https://docs.microsoft.com/powershell/module/sharepoint-online/Set-SPOTenant?view=sharepoint-ps) cmdlet ar parametru **DisallowInfectedFileDownload** , kas iestatīts kā *patiess* .</span><span class="sxs-lookup"><span data-stu-id="5548a-106">(Recommended) As a global administrator or a SharePoint Online administrator, run the [Set-SPOTenant](https://docs.microsoft.com/powershell/module/sharepoint-online/Set-SPOTenant?view=sharepoint-ps) cmdlet with the **DisallowInfectedFileDownload** parameter set to *true* .</span></span>
5. <span data-ttu-id="5548a-107">Ieteicams [Iestatiet brīdinājumus](https://docs.microsoft.com/microsoft-365/security/office-365-security/turn-on-atp-for-spo-odb-and-teams#set-up-alerts-for-detected-files) par noteiktajiem failiem.</span><span class="sxs-lookup"><span data-stu-id="5548a-107">(Recommended) [Set up alerts](https://docs.microsoft.com/microsoft-365/security/office-365-security/turn-on-atp-for-spo-odb-and-teams#set-up-alerts-for-detected-files) for detected files.</span></span>

> [!NOTE]
> <span data-ttu-id="5548a-108">ATP ir NTO skenē katru atsevišķu failu pakalpojumā SharePoint Online, OneDrive vai Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="5548a-108">ATP will nto scan every single file in SharePoint Online, OneDrive, or Microsoft Teams.</span></span> <span data-ttu-id="5548a-109">Faili tiek skenēti asinhroni, izmantojot procesu, kas izmanto koplietošanas un viesa aktivitāšu notikumus, kā arī viedos heiristiku un draudu signālus, lai identificētu ļaunprātīgus failus.</span><span class="sxs-lookup"><span data-stu-id="5548a-109">Files are scanned asynchronously, through a process that uses sharing and guest activity events, along with smart heuristics and threat signals to identify malicious files.</span></span> <span data-ttu-id="5548a-110">Skatiet rakstu [ATP for SharePoint, OneDrive un Microsoft Teams](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams).</span><span class="sxs-lookup"><span data-stu-id="5548a-110">See [ATP for SharePoint, OneDrive, and Microsoft Teams](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams).</span></span>