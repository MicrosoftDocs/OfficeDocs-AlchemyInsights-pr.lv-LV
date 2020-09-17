---
title: SharePoint Online ierobežošana
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: b376d8ea-50c4-47f0-9720-50d80aa3f7f1
ms.custom:
- "9000149"
- "1662"
- "3491"
ms.openlocfilehash: 21d0f8d0118d92562b425921742513157563b5fb
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: lv-LV
ms.lasthandoff: 09/15/2020
ms.locfileid: "47773854"
---
# <a name="sharepoint-online-throttling"></a><span data-ttu-id="6a249-102">SharePoint Online ierobežošana</span><span class="sxs-lookup"><span data-stu-id="6a249-102">SharePoint Online Throttling</span></span>

<span data-ttu-id="6a249-103">**Svarīgi**: šo bezprecedenta laiku mēs veicam darbības, lai nodrošinātu, ka SharePoint Online un OneDrive pakalpojumi joprojām ir plaši pieejami. Lai iegūtu papildinformāciju, apmeklējiet [SharePoint Online pagaidu līdzekļu pielāgojumi](https://aka.ms/ODSPAdjustments).</span><span class="sxs-lookup"><span data-stu-id="6a249-103">**Important**: During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available – Please visit [SharePoint Online Temporary Feature Adjustments](https://aka.ms/ODSPAdjustments) for more information.</span></span>

<span data-ttu-id="6a249-104">**503 serveris ir aizņemts kļūdas ziņojums**</span><span class="sxs-lookup"><span data-stu-id="6a249-104">**503 server is busy error**</span></span>

<span data-ttu-id="6a249-105">Mēģinot veikt navigāciju uz SharePoint vai OneDrive vietnēm, lietotāji var saņemt 503 serveri ir aizņemts.</span><span class="sxs-lookup"><span data-stu-id="6a249-105">Users may receive a 503 server is busy error when attempting to navigate to SharePoint or OneDrive sites.</span></span> 

<span data-ttu-id="6a249-106">Šo kļūdu var izraisīt ierobežošana SharePoint pakalpojumā.</span><span class="sxs-lookup"><span data-stu-id="6a249-106">This error can be caused by throttling within the SharePoint service.</span></span> <span data-ttu-id="6a249-107">SharePoint Online izmanto ierobežošanu, lai uzturētu optimālu SharePoint Online pakalpojuma veiktspēju un uzticamību.</span><span class="sxs-lookup"><span data-stu-id="6a249-107">SharePoint Online uses throttling to maintain optimal performance and reliability of the SharePoint Online service.</span></span> <span data-ttu-id="6a249-108">Ierobežošana ierobežo lietotāju darbību vai vienlaicīgu zvanu skaitu (ar skriptu vai kodu), lai nepieļautu pārmērīgu resursu pielietojumu.</span><span class="sxs-lookup"><span data-stu-id="6a249-108">Throttling limits the number of user actions or concurrent calls (by script or code) to prevent overuse of resources.</span></span> 

<span data-ttu-id="6a249-109">Papildinformāciju par ierobežošanu skatiet rakstā Neļaujiet ierobežot [vai bloķēt pakalpojumā SharePoint Online](https://docs.microsoft.com/sharepoint/dev/general-development/how-to-avoid-getting-throttled-or-blocked-in-sharepoint-online).</span><span class="sxs-lookup"><span data-stu-id="6a249-109">For more information on throttling see, [Avoid getting throttled or blocked in SharePoint Online](https://docs.microsoft.com/sharepoint/dev/general-development/how-to-avoid-getting-throttled-or-blocked-in-sharepoint-online).</span></span>

<span data-ttu-id="6a249-110">Ja uzskatāt, ka šī kļūda nav saistīta ar ierobežošanu, varat pārbaudīt, vai nomniekā tiek rādīta aktīva uzturēšana, naviģējot līdz [ziņojumu centram](https://portal.office.com/adminportal/home#/MessageCenter).</span><span class="sxs-lookup"><span data-stu-id="6a249-110">If you believe this error is unrelated to throttling, you can check if there is active maintenance occurring on your tenant by navigating to the [Message center](https://portal.office.com/adminportal/home#/MessageCenter).</span></span>

 <span data-ttu-id="6a249-111">Visbeidzot, pārliecinieties, vai esat apmeklējis [pakalpojumu darbspējas](https://portal.office.com/adminportal/home#/servicehealth) lapu, lai noskaidrotu, vai nav konsultantu/incidentu, kas var notikt.</span><span class="sxs-lookup"><span data-stu-id="6a249-111">Finally, ensure you visit the [Service Health](https://portal.office.com/adminportal/home#/servicehealth) page to check for any advisories/incidents that may be occurring.</span></span>

