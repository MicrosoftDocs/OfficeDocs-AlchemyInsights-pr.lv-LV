---
title: Access pakalpojumu pensijas
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "9000356"
- "2009"
ms.assetid: ''
ms.openlocfilehash: 943066d5ac76c0630554ee724bbab9a94086fae4
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: lv-LV
ms.lasthandoff: 09/14/2020
ms.locfileid: "47698689"
---
# <a name="access-services-retirement"></a><span data-ttu-id="edb17-102">Access pakalpojumu pensijas</span><span class="sxs-lookup"><span data-stu-id="edb17-102">Access services retirement</span></span>

<span data-ttu-id="edb17-103">Tā kā mēs sākotnēji izziņojām MC97576, 2017. gada martā un turpinājām sazināties ar Access pakalpojumu iepriekšējo gadu.</span><span class="sxs-lookup"><span data-stu-id="edb17-103">As we originally announced in MC97576, in March 2017, and continued to communicate over the past year Access Services are being retired.</span></span> <span data-ttu-id="edb17-104">Nākamajā šī procesa posmā tiks noņemtas Access tīmekļa datu bāzes, kas izmanto SharePoint sarakstus kā pamatā esošo datu krātuvi.</span><span class="sxs-lookup"><span data-stu-id="edb17-104">The next phase in this process will be the removal of Access Web Databases that use SharePoint lists as their underlying data storage.</span></span>

<span data-ttu-id="edb17-105">**Kā tas ietekmē mani?**</span><span class="sxs-lookup"><span data-stu-id="edb17-105">**How does this affect me?**</span></span>

<span data-ttu-id="edb17-106">Sākot ar 2019. jūnija beigām, mēs pārtrauks izveidot jaunas Access datu bāzes pakalpojumā SharePoint Online, kā arī beidzēt pakalpojumu un visas pārējās 2020 programmas.</span><span class="sxs-lookup"><span data-stu-id="edb17-106">Starting June 2019, we will stop creation of new Access databases in SharePoint Online and shut down the service and any remaining apps by April 2020.</span></span>

<span data-ttu-id="edb17-107">**Kas ir jādara, lai sagatavotos izmaiņām?**</span><span class="sxs-lookup"><span data-stu-id="edb17-107">**What do I need to do to prepare for this change?**</span></span>

<span data-ttu-id="edb17-108">Mēs aicinām jūs izveidot pārejas plānu savas organizācijas Access tīmekļa datu bāzēm.</span><span class="sxs-lookup"><span data-stu-id="edb17-108">We encourage you to create a transition plan for your organization's Access web databases.</span></span> <span data-ttu-id="edb17-109">Administratori var izmantot [SharePoint Access lietojumprogrammas skeneri](https://github.com/SharePoint/PnP-Tools/tree/master/Solutions/SharePoint.AccessApp.Scanner) , lai iegūtu to Access lietojumprogrammu sarakstu, kuras izmanto vietnes.</span><span class="sxs-lookup"><span data-stu-id="edb17-109">Admins can use the [SharePoint Access app scanner](https://github.com/SharePoint/PnP-Tools/tree/master/Solutions/SharePoint.AccessApp.Scanner) to obtain an inventory of the Access apps that sites are using.</span></span>

<span data-ttu-id="edb17-110">Pastāv vairāki veidi, kā migrēt Access tīmekļa datu bāzes datus.</span><span class="sxs-lookup"><span data-stu-id="edb17-110">There are several ways to migrate Access web databases data:</span></span>

- <span data-ttu-id="edb17-111">Importēšana lokālajā Access datu bāzē (. ACCDB) vai Excel failā.</span><span class="sxs-lookup"><span data-stu-id="edb17-111">Importing to a local Access database (.ACCDB) or to an Excel file.</span></span>
- <span data-ttu-id="edb17-112">Iesakām arī izpētīt Microsoft PowerApps kā alternatīvu platformu, lai izveidotu bez koda biznesa risinājumus tīmeklī un mobilajām ierīcēm.</span><span class="sxs-lookup"><span data-stu-id="edb17-112">We also recommend exploring Microsoft PowerApps as an alternative platform to create no-code business solutions for web and mobile devices.</span></span>