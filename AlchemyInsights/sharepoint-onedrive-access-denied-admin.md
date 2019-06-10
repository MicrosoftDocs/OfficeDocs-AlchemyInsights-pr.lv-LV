---
title: Novērst problēmas ziņojumu piekļuve liegta
ms.author: kirks
author: Techwriter40
ms.date: 6/29/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: d678b57a-53ad-4414-9423-d8726a0c532f
ms.openlocfilehash: c204f1889e03886fdfd3d1c760a4a2beb82b0836
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: lv-LV
ms.lasthandoff: 06/07/2019
ms.locfileid: "34760347"
---
# <a name="troubleshoot-access-denied-messages-in-sharepointonedrive-admin-center"></a>Problēmu novēršana darbā ar Sharepoint/OneDrive administrēšanas centrā ziņojumi Piekļuve liegta

Ja saņemat ziņojumu par liegtu piekļuvi, mēģinot meklēt Sharepoint/OneDrive Admin Center, lūdzu, pārliecinieties, ka jums [piešķirt licenci lietotājam](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/assign-licenses-to-users?view=o365-worldwide&amp;tabs=One). Ja lietotājam ir licence, jums vajadzētu arī pārliecināties tie ir [piešķirta administratora loma](https://docs.microsoft.com/office365/admin/add-users/about-admin-roles?view=o365-worldwide) , var piekļūt admin centriem.

Šī problēma var arī rasties, ja lietotājs ir dzēsta un izveidota atkārtoti, izmantojot vienu un to pašu lietotāja pamatnosaukums (UPN). Jaunais konts ir izveidots, izmantojot citu PUID (pases unikālo ID) vērtību. Ja lietotājs mēģina piekļūt vietņu kolekcijā vai to OneDrive, lietotājam ir nepareiza PUID. Otrais scenārijs ietver directory sinhronizācija ar Active Directory organizācijas vienību (OU). Ja lietotāji jau pieslēdzās SharePoint, un tad ir pārvietots uz citu OU un resynced ar SharePoint, viņiem šī problēma var rasties.

Lai atrisinātu šo problēmu, vajadzētu atjaunot sākotnējo UPN ar rakstu, [atjaunot Office 365 lietotāja](https://docs.microsoft.com/office365/admin/add-users/restore-user?view=o365-worldwide)darbības.

Piezīme: Ja OneDrive vai SharePoint administrēšanas centru nav pieejams vairākiem lietotājiem, kas iepriekš bija pieejams, var rasties pagaidu pakalpojumu jautājums.  [Pārbaudiet pakalpojumu veselības vadības paneli](https://portal.office.com/adminportal/home#/servicehealth).

