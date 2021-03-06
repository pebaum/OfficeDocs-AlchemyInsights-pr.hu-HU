---
title: A SharePoint- és OneDrive-értesítések fogadásának késedelme
ms.author: v-todmc
author: todmccoy
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000118"
- "2642"
ms.openlocfilehash: fb7ab6e8139c46d89b1cae1ee0ab9b9a601c8b64
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: hu-HU
ms.lasthandoff: 04/22/2020
ms.locfileid: "43742003"
---
# <a name="delays-in-receiving-sharepoint-and-onedrive-alerts"></a>A SharePoint- és OneDrive-értesítések fogadásának késedelme

- Először ellenőrizze a Levélszemét vagy Spam mappát az e-mailben.
- Ha **több fájl vagy tárak összes riasztása késik,** látogasson el a [Szolgáltatásállapot irányítópultjára,](https://portal.office.com/adminportal/home?ref=/servicehealth) és ellenőrizze, hogy vannak-e olyan tanácsok/incidensek, amelyek a SharePoint vagy az Exchange alkalmazásban előfordulhatnak. A probléma lehet a SharePoint riasztási képesség vagy késedelmek e-mailek az Exchange-en keresztül. Azt is vegye figyelembe, hogy más e-maileket kézbesítenek-e – ha nem, akkor a probléma valószínűleg az Exchange késéseivel van.
- Ha **egy adott fájlból vagy tárból származó egyéni riasztás nem jelenik meg,** próbálja meg törölni és újra létrehozni. A riasztás újbóli létrehozásához olvassa el A [SharePoint-értesítések kezelése, megtekintése és törlése](https://support.microsoft.com/office/manage-view-or-delete-sharepoint-alerts-99dfb19c-9a90-4a8c-aba1-aa8c8afb0de2) című témakört.

> [!NOTE]
> - Terjesztési csoportnak nem lehet értesítéseket küldeni. Csak a Biztonság és az O365 csoportok támogatottak.
> - A figyelmeztető e-mail sablonok nem szabhatók testre. Ezek eléréséhez microsoft flow vagy SharePoint Designer munkafolyamatot kell használnia.
