---
title: Lietojumprogrammas starpniekservera konfigurācija
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
- "9004356"
- "7800"
ms.openlocfilehash: 0b782705afa8eab338687590baff90de4e17ccb9
ms.sourcegitcommit: 83fe2a8d060794fdf58445b469b30a3294b7a9b6
ms.translationtype: MT
ms.contentlocale: lv-LV
ms.lasthandoff: 01/15/2021
ms.locfileid: "49885136"
---
# <a name="app-proxy-configuration"></a><span data-ttu-id="3964d-102">Lietojumprogrammas starpniekservera konfigurācija</span><span class="sxs-lookup"><span data-stu-id="3964d-102">App Proxy Configuration</span></span>

1. <span data-ttu-id="3964d-103">Lai izprastu, kā konfigurēt lietojumprogrammas starpniekservera lietojumprogrammu Azure AD, lai lokālās lietojumprogrammas atklātu mākonī, skatiet rakstu [kā konfigurēt lietojumprogrammas starpniekservera lietojumprogrammu](https://docs.microsoft.com/azure/active-directory/application-proxy-config-how-to).</span><span class="sxs-lookup"><span data-stu-id="3964d-103">To understand how to configure an Application Proxy application within Azure AD to expose your on-premises applications to the cloud, see [How to configure an Application Proxy application](https://docs.microsoft.com/azure/active-directory/application-proxy-config-how-to).</span></span>
2. <span data-ttu-id="3964d-104">Vienotā pierakstīšanās (SSO) ļauj lietotājiem piekļūt lietojumprogrammai, neveicot autentificēšanas vairākas reizes.</span><span class="sxs-lookup"><span data-stu-id="3964d-104">Single sign-on (SSO) allows your users to access an application without authenticating multiple times.</span></span> <span data-ttu-id="3964d-105">Tas ļauj vienai autentifikācijai notikt mākonī, izmantojot Azure Active Directory, un ļauj pakalpojumam vai savienotājam personificēt lietotāju, lai pabeigtu jebkādas papildu autentifikācijas problēmas no lietojumprogrammas.</span><span class="sxs-lookup"><span data-stu-id="3964d-105">It allows the single authentication to occur in the cloud, against Azure Active Directory, and allows the service or Connector to impersonate the user to complete any additional authentication challenges from the application.</span></span> <span data-ttu-id="3964d-106">Papildinformāciju skatiet rakstā [vienotās pierakstīšanās konfigurācija lietojumprogrammas starpniekservera lietojumprogrammai](https://docs.microsoft.com/azure/active-directory/application-proxy-config-sso-how-to).</span><span class="sxs-lookup"><span data-stu-id="3964d-106">To learn more, see [How to configure single sign-on to an Application Proxy application](https://docs.microsoft.com/azure/active-directory/application-proxy-config-sso-how-to).</span></span>
3. <span data-ttu-id="3964d-107">Izmantojiet [šo rakstu](https://docs.microsoft.com/azure/active-directory/application-proxy-config-problem) , lai novērstu bieži sastopamas problēmas, ar kurām saskaras lietotāji, veidojot jaunu lietojumprogrammas starpniekservera lietojumprogrammu.</span><span class="sxs-lookup"><span data-stu-id="3964d-107">Use [this article](https://docs.microsoft.com/azure/active-directory/application-proxy-config-problem) to troubleshoot common issues people face when creating a new application proxy application.</span></span>
4. <span data-ttu-id="3964d-108">Ja rodas problēmas, iestatot servera autentifikācijas autentifikāciju savā lietojumprogrammā, iespējams, ir [jānovērš Kerberos ierobežotās deleģēšanas konfigurācijas lietojumprogrammas starpniekserverim](https://docs.microsoft.com/azure/active-directory/application-proxy-back-end-kerberos-constrained-delegation-how-to) vai jāievēro norādījumi par [lietojumprogrammas konfigurēšanu ar PingAccess](https://docs.microsoft.com/azure/active-directory/application-proxy-back-end-ping-access-how-to) , lai atrisinātu problēmu.</span><span class="sxs-lookup"><span data-stu-id="3964d-108">If you are having a problem setting up back-end authentication to your application you may need to [Troubleshoot Kerberos constrained delegation configurations for Application Proxy](https://docs.microsoft.com/azure/active-directory/application-proxy-back-end-kerberos-constrained-delegation-how-to) or follow guidance on [configuring application with PingAccess](https://docs.microsoft.com/azure/active-directory/application-proxy-back-end-ping-access-how-to) to resolve your issue.</span></span>
