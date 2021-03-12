---
title: Biežāk sastopamo problēmu novēršana saistībā ar DKIM ieraksta formatēšanu
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 02/23/2021
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9002531"
- "7375"
ms.openlocfilehash: 0a59ca1c93121cb4681c0d44b85a9b756c07895b
ms.sourcegitcommit: 6312ee31561db36104f32282d019d069ede69174
ms.translationtype: MT
ms.contentlocale: lv-LV
ms.lasthandoff: 03/11/2021
ms.locfileid: "50746832"
---
# <a name="fix-common-problems-with-dkim-record-formatting"></a><span data-ttu-id="60d7f-102">Biežāk sastopamo problēmu novēršana saistībā ar DKIM ieraksta formatēšanu</span><span class="sxs-lookup"><span data-stu-id="60d7f-102">Fix common problems with DKIM record formatting</span></span>

<span data-ttu-id="60d7f-103">Lielākā daļa DKIM iestatīšanas problēmu ir saistītas ar nepareiziem DNS ierakstiem.</span><span class="sxs-lookup"><span data-stu-id="60d7f-103">Most DKIM set-up issues are related to incorrect DNS records.</span></span>

<span data-ttu-id="60d7f-104">Lai izlabotu DKIM iestatīšanas problēmas, pārbaudiet, vai DKIM CNAME ieraksts (**nevis** txt ieraksts) ir pareizi formatēts.</span><span class="sxs-lookup"><span data-stu-id="60d7f-104">To fix the DKIM set-up issues, verify that the DKIM CNAME record (**not** a TXT record) is formatted correctly.</span></span> <span data-ttu-id="60d7f-105">Papildinformāciju skatiet rakstā kas jādara, [lai manuāli IESTATĪTU DKIM pakalpojumā Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/use-dkim-to-validate-outbound-email).</span><span class="sxs-lookup"><span data-stu-id="60d7f-105">For more information, see [What you need to do to manually set up DKIM in Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/use-dkim-to-validate-outbound-email).</span></span>

<span data-ttu-id="60d7f-106">Ja vēlaties saņemt palīdzību par DNS ierakstiem vispār, skatiet rakstu [DNS ierakstu izveide pie jebkura DNS viesošanas pakalpojumu sniedzēja pakalpojumā Office 365](https://docs.microsoft.com/microsoft-365/admin/get-help-with-domains/create-dns-records-at-any-dns-hosting-provider).</span><span class="sxs-lookup"><span data-stu-id="60d7f-106">If you need help with DNS records in general, see [Create DNS records at any DNS hosting provider for Office 365](https://docs.microsoft.com/microsoft-365/admin/get-help-with-domains/create-dns-records-at-any-dns-hosting-provider).</span></span>

> [!NOTE]
> <span data-ttu-id="60d7f-107">Pēc tam, kad esat izveidojis vai atjauninājis savus DKIM DNS ierakstus pie sava domēna DNS viesošanas pakalpojuma, būs jāgaida, līdz tiek izplatīti DNS ieraksti.</span><span class="sxs-lookup"><span data-stu-id="60d7f-107">After you create or update your DKIM DNS records at the DNS hosting service for your domain, you'll need to wait for the DNS records to propagate.</span></span>