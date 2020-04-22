---
title: ConsistencyGuid/sourceAnchor darbība
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 6a44f797-acc7-4cbe-aa5a-47e2581fabf5
ms.openlocfilehash: 8527e7c2404742a999041f85ed12d78c48cc0d8c
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: lv-LV
ms.lasthandoff: 04/22/2020
ms.locfileid: "43705740"
---
# <a name="consistencyguid--sourceanchor-behavior"></a><span data-ttu-id="1d0f0-102">ConsistencyGuid/sourceAnchor darbība</span><span class="sxs-lookup"><span data-stu-id="1d0f0-102">ConsistencyGuid / sourceAnchor behavior</span></span>

<span data-ttu-id="1d0f0-103">Azure AD savienojumu (Version 1.1.524.0 un pēc) tagad atvieglo izmantot BKAS-ConsistencyGuid kā sourceAnchor atribūtu.</span><span class="sxs-lookup"><span data-stu-id="1d0f0-103">Azure AD Connect (version 1.1.524.0 and after) now facilitates the use of msDS-ConsistencyGuid as sourceAnchor attribute.</span></span> <span data-ttu-id="1d0f0-104">Izmantojot šo līdzekli, Azure AD Connect automātiski konfigurē sinhronizācijas kārtulas:</span><span class="sxs-lookup"><span data-stu-id="1d0f0-104">When using this feature, Azure AD Connect automatically configures the synchronization rules to:</span></span>
  
- <span data-ttu-id="1d0f0-105">Izmantojiet msDS-ConsistencyGuid kā sourceAnchor atribūtu lietotāja objektiem.</span><span class="sxs-lookup"><span data-stu-id="1d0f0-105">Use msDS-ConsistencyGuid as the sourceAnchor attribute for User objects.</span></span> <span data-ttu-id="1d0f0-106">ObjectGUID tiek izmantots citiem objektu tipiem.</span><span class="sxs-lookup"><span data-stu-id="1d0f0-106">ObjectGUID is used for other object types.</span></span>
    
- <span data-ttu-id="1d0f0-107">Jebkuru lokālo reklāmas lietotāja objekts, kura BKAS ConsistencyGuid atribūts nav aizpildīts, Azure AD savienojumu raksta objectGUID vērtību atpakaļ uz lokālo Active Directory atribūtu msDS-ConsistencyGuid.</span><span class="sxs-lookup"><span data-stu-id="1d0f0-107">For any given on-premises AD User object whose msDS-ConsistencyGuid attribute isn't populated, Azure AD Connect writes its objectGUID value back to the msDS-ConsistencyGuid attribute in on-premises Active Directory.</span></span> <span data-ttu-id="1d0f0-108">Pēc tam, kad BKAS ConsistencyGuid atribūts ir aizpildīts, Azure AD savienojumu pēc tam eksportē objektu Azure AD.</span><span class="sxs-lookup"><span data-stu-id="1d0f0-108">After the msDS-ConsistencyGuid attribute is populated, Azure AD Connect then exports the object to Azure AD.</span></span>
    
 <span data-ttu-id="1d0f0-109">**Piezīme:** Kad lokālas reklāmas objekts tiek importēts Azure AD savienojumu (tas ir, importēt uz AD Connector telpas un projicē metaverse), nevar mainīt tās sourceAnchor vērtība vairs.</span><span class="sxs-lookup"><span data-stu-id="1d0f0-109">**Note:** Once an on-premises AD object is imported into Azure AD Connect (that is, imported into the AD Connector Space and projected into the Metaverse), you cannot change its sourceAnchor value anymore.</span></span> <span data-ttu-id="1d0f0-110">Lai norādītu lokālā reklāmas objekta sourceAnchor vērtību, konfigurējiet tā BKAS ConsistencyGuid atribūtu, pirms tas tiek importēts Azure AD savienojumu.</span><span class="sxs-lookup"><span data-stu-id="1d0f0-110">To specify the sourceAnchor value for a given on-premises AD object, configure its msDS-ConsistencyGuid attribute before it is imported into Azure AD Connect.</span></span> 
  
<span data-ttu-id="1d0f0-111">Lai iegūtu papildinformāciju par SourceAnchor un ConsistencyGuid, skatiet šo: [AZURE ad Connect: dizaina koncepcijas](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-design-concepts)</span><span class="sxs-lookup"><span data-stu-id="1d0f0-111">For more information on SourceAnchor and ConsistencyGuid, refer to the following: [Azure AD Connect: Design concepts](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-design-concepts)</span></span>
  

