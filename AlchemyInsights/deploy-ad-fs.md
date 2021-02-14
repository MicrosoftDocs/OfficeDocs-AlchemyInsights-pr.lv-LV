---
title: Izvietošanas AD FS
ms.author: v-jmathew
author: v-jmathew
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "1300012"
- "7420"
ms.openlocfilehash: a304504f7483036884878639dfa6ebfc3cdfcac8
ms.sourcegitcommit: 05a9dd3121c21322dc9ddec4c2eec548cafd5a43
ms.translationtype: MT
ms.contentlocale: lv-LV
ms.lasthandoff: 02/09/2021
ms.locfileid: "50177543"
---
# <a name="deploy-ad-fs"></a><span data-ttu-id="5a610-102">Izvietošanas AD FS</span><span class="sxs-lookup"><span data-stu-id="5a610-102">Deploy AD FS</span></span>

<span data-ttu-id="5a610-103">Active Directory Federācijas pakalpojums (AD FS) izvietošana izmanto jūsu lokālo infrastruktūru, lai autentificētu lietotājus Office 365 pakalpojumos.</span><span class="sxs-lookup"><span data-stu-id="5a610-103">An Active Directory Federation Services (AD FS) deployment uses your on-premises infrastructure to authenticate users for ‎Office 365 services.</span></span> <span data-ttu-id="5a610-104">Izmantojot ārēju pierakstīšanos, varat iespējot lietotājiem pierakstīties pakalpojumā Office 365 Services un programmatūrā kā pakalpojuma (SAAS) lietojumprogrammas, kas ir integrētas Azure Active Directory (Azure AD).</span><span class="sxs-lookup"><span data-stu-id="5a610-104">With federated sign-in, you can enable users to sign in to Office 365 services and Software as a Service (SAAS) applications that are integrated with Azure Active Directory (Azure AD).</span></span> <span data-ttu-id="5a610-105">Federatīvajās pierakstīšanās autentificēti lietotāji no lokālā Active Directory, izmantojot AD FS.</span><span class="sxs-lookup"><span data-stu-id="5a610-105">Federated sign-in authenticates users against your on-premises Active Directory via AD FS.</span></span> <span data-ttu-id="5a610-106">Arī korporatīvā tīkla lietotājiem nav nepieciešams atkārtoti ievadīt paroles.</span><span class="sxs-lookup"><span data-stu-id="5a610-106">Also, while on the corporate network, users won't be required to reenter their passwords.</span></span>

<span data-ttu-id="5a610-107">[AD FS izvietošanas padomnieks](https://go.microsoft.com/fwlink/?linkid=2071178) nodrošina detalizētus norādījumus par LOKĀLĀS AD FS infrastruktūras izvietošanu, kas autentificē lietotājus Microsoft 365 un Office 365 pakalpojumos.</span><span class="sxs-lookup"><span data-stu-id="5a610-107">The [AD FS deployment advisor](https://go.microsoft.com/fwlink/?linkid=2071178) provides you with step-by-step guidance on deploying an on-premises AD FS infrastructure that authenticates users for Microsoft 365 and Office 365 services.</span></span> <span data-ttu-id="5a610-108">Izmantojot šo rokasgrāmatu, jūsu organizācija var pārskatīt AD FS komponentus un prasības, iegūt un instalēt SSL sertifikātus, kas nepieciešami izvietošanai, un instalēt nepieciešamo tīmekļa lietojumprogrammas starpniekserveri.</span><span class="sxs-lookup"><span data-stu-id="5a610-108">With this guide, your organization can review AD FS components and requirements, acquire and install SSL certificates that are necessary for deployment, and install a required web application proxy server.</span></span>