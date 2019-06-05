---
title: Pamati darbam ar SharePoint Online
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 7ae05f21-eb16-4d71-9e19-4f097eb100d2
ms.openlocfilehash: 9a8d72a01ed35794fcab370b48bbb189663d3396
ms.sourcegitcommit: 6d341637dbb14e90726a1ce1d68f077ace9bb765
ms.translationtype: MT
ms.contentlocale: lv-LV
ms.lasthandoff: 06/04/2019
ms.locfileid: "34718753"
---
# <a name="workflows-in-sharepoint"></a><span data-ttu-id="2879c-102">Darbplūsmas, koplietošanas vidē SharePoint</span><span class="sxs-lookup"><span data-stu-id="2879c-102">Workflows in SharePoint</span></span>

<p><span data-ttu-id="2879c-103">Ja SharePoint darbplūsmas nesūta e-pastu, jūsu organizācija ir konstatējis Exchange Online sūtītāja robežas.&nbsp;</span><span class="sxs-lookup"><span data-stu-id="2879c-103">If SharePoint workflows are not sending emails, your organization may have encountered the Exchange Online sender limits.&nbsp;</span></span></p> <p><span data-ttu-id="2879c-104">"Darba plūsma tiks pārtraukta" kļūdas ziņojums var rasties, ja esat viens no šiem vienumiem:</span><span class="sxs-lookup"><span data-stu-id="2879c-104">'Workflow is Suspended' error message may occur if you have one of the following items:</span></span></p> <ul> <li><span data-ttu-id="2879c-105">Darbplūsma ir SharePoint Online, kas izmanto SharePoint 2010 vai SharePoint 2013 darbplūsmas platformas tipa.</span><span class="sxs-lookup"><span data-stu-id="2879c-105">You have a workflow in SharePoint Online that's using the SharePoint 2010 or SharePoint 2013 workflow platform type.</span></span></li> <li><span data-ttu-id="2879c-106">Darbplūsma ir konfigurēta, lai nosūtītu pielāgotus e-pasta ziņu vairāk nekā 200 lietotājiem laikā, vairāk nekā 10000 adresāti dienā vai vairāk nekā 30 ziņojumi minūtē.</span><span class="sxs-lookup"><span data-stu-id="2879c-106">The workflow is configured to send a custom email message to more than 200 users at a time, more than 10,000 recipients per day, or more than 30 messages per minute.</span></span></li> <li><span data-ttu-id="2879c-107">Darbojas darbplūsma, e-pasta ziņa nav nosūtīta un pamanāt kļūdas ziņojumu, <strong>iekšējais statuss ir iestatīts uz apturēts</strong> vai <strong>nevar nosūtīt adresātam</strong> tiek parādīts.</span><span class="sxs-lookup"><span data-stu-id="2879c-107">When you run the workflow, the email message isn't sent, and you notice the error message, <strong>Internal Status is set to Suspended</strong> or <strong>Unable to send to a recipient</strong> is displayed.</span></span></li> </ul> <p><span data-ttu-id="2879c-108">Lai iegūtu papildinformāciju, skatiet šādu <a href="https://support.office.com/en-us/article/-daily-email-limit-has-exceeded-and-your-workflow-has-been-suspended-or-unable-to-send-to-a-recipient-error-in-a-sharepoint-online-workflow-89d02169-5fa6-4259-affc-73edb6ca9fb6?ui=en-US&amp;rs=en-US&amp;ad=US">pantu</a>.</span><span class="sxs-lookup"><span data-stu-id="2879c-108">For more information, please refer to the following <a href="https://support.office.com/en-us/article/-daily-email-limit-has-exceeded-and-your-workflow-has-been-suspended-or-unable-to-send-to-a-recipient-error-in-a-sharepoint-online-workflow-89d02169-5fa6-4259-affc-73edb6ca9fb6?ui=en-US&amp;rs=en-US&amp;ad=US">article</a>.</span></span></p>

