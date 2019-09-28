---
title: Izejošais e-pasts uz mapi Nevēlamais e-pasts
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "2697"
ms.assetid: ''
ms.openlocfilehash: 371d2c46e9048365fd343145330536bd9cf1db82
ms.sourcegitcommit: 1002f510fadb92c143cd6bbb60b42a851d5a38e1
ms.translationtype: MT
ms.contentlocale: lv-LV
ms.lasthandoff: 09/20/2019
ms.locfileid: "37062804"
---
# <a name="outbound-email-to-junk-email-folder"></a><span data-ttu-id="63c25-102">Izejošais e-pasts uz mapi Nevēlamais e-pasts</span><span class="sxs-lookup"><span data-stu-id="63c25-102">Outbound email to Junk Email folder</span></span>

<span data-ttu-id="63c25-103">Ja redzat, ka izejošie ziņojumi tiek atzīmēti kā nevēlami, veiciet šādas darbības:</span><span class="sxs-lookup"><span data-stu-id="63c25-103">If you're seeing outbound messages being marked as Junk, do the following steps:</span></span>

- <span data-ttu-id="63c25-104">Ja vēl neesat to izdarījis, apsveriet iespēju [konfigurēt izejošos surogātpasta politikas paziņojumus](https://docs.microsoft.com/office365/securitycompliance/configure-the-outbound-spam-policy).</span><span class="sxs-lookup"><span data-stu-id="63c25-104">If you haven't already, consider [configuring outbound spam policy notifications](https://docs.microsoft.com/office365/securitycompliance/configure-the-outbound-spam-policy).</span></span>

- <span data-ttu-id="63c25-105">Izmantojiet [ziņojumu izsekošana](https://docs.microsoft.com/office365/securitycompliance/message-trace-scc) , lai redzētu, vai izejošo ziņojumu **surogātpasta** notikuma vērtību ar papildu detaļas: **Izmantojiet augsta riska piegādes pūls**.</span><span class="sxs-lookup"><span data-stu-id="63c25-105">Use [message trace](https://docs.microsoft.com/office365/securitycompliance/message-trace-scc) to see if the outbound message has the event value **Spam** with the additional detail: **Use high risk delivery pool**.</span></span>

  <span data-ttu-id="63c25-106">Šiem ziņojumiem pārbaudiet ziņojuma saturu, lai redzētu, kas varētu tikt uzskatīts par surogātpastu.</span><span class="sxs-lookup"><span data-stu-id="63c25-106">For these messages, check the message content to see what might be considered spam.</span></span> <span data-ttu-id="63c25-107">Piemēram, paraksti dažreiz var radīt problēmas daudziem lietotājiem.</span><span class="sxs-lookup"><span data-stu-id="63c25-107">For example, signatures can sometimes cause problems for many users.</span></span>

  <span data-ttu-id="63c25-108">Ja jums ir vairāki piemēri likumīgu izejošo ziņojumu, kas tiek atzīmēts kā nevēlams, atveriet atbalsta biļeti un lūdziet atbalsta aģents iesniegt ziņojumus kā viltus pozitīvi mūsu surogātpasta analītiķiem.</span><span class="sxs-lookup"><span data-stu-id="63c25-108">If you have multiple examples of legitimate outbound messages that are being marked as Junk, open a support ticket and ask the support agent to submit your messages as false positives to our spam analysts.</span></span> <span data-ttu-id="63c25-109">Esiet gatavi sniegt parauga ziņojumus, kas ietver visas ziņojumu galvenes.</span><span class="sxs-lookup"><span data-stu-id="63c25-109">Be prepared to provide sample messages that include all message headers.</span></span>