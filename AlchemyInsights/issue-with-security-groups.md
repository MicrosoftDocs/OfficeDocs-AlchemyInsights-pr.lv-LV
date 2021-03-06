---
title: Problēma ar drošības grupām
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 02/09/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "8252"
- "9004397"
ms.openlocfilehash: 1198b79c3301bd2752a7385a6ba6746c8f0c2b5b
ms.sourcegitcommit: 22eaf0a151ab95414476f596db8d318b6540ff31
ms.translationtype: MT
ms.contentlocale: lv-LV
ms.lasthandoff: 02/09/2021
ms.locfileid: "50177498"
---
# <a name="issue-with-security-groups"></a>Problēma ar drošības grupām

**Ja saņemat tīkla kļūdu AADDS104**

Nederīgi tīkla drošības grupas kārtulas ir visbiežāk sastopamais tīkla kļūdu cēlonis Azure Active Directory domēna pakalpojumos (AD DS). Virtuālā tīkla tīkla drošības grupai ir jāatļauj piekļūt konkrētiem portiem un protokoliem. Ja šie porti ir bloķēti, Azure Platform nevar pārraudzīt vai atjaunināt pārvaldīto domēnu. Tiek ietekmēta arī sinhronizēšana starp Azure AD un Azure AD DS. Pārliecinieties, vai ir pieejami noklusējuma porti, lai izvairītos no pakalpojuma darbības traucējumiem.

Lai izprastu un novērstu vispārējus brīdinājumus par tīkla drošības grupas konfigurācijas problēmām, skatiet rakstu [drošības grupu pievienošana un pārbaude](https://docs.microsoft.com/azure/active-directory-domain-services/alert-nsg#verify-and-edit-existing-security-rules).
