---
title: Felhasználók hozzáférésének biztosítása a SharePoint és a OneDrive
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.date: 11/14/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: cebb7a4a-33e1-474e-a5d0-dbd02a80b1e9
ms.openlocfilehash: a689769dab24e12832ddc0937bc5ddc3d71dbee3
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: hu-HU
ms.lasthandoff: 06/07/2019
ms.locfileid: "34759258"
---
# <a name="give-users-access-to-sharepoint-and-onedrive"></a>Felhasználók hozzáférésének biztosítása a SharePoint és a OneDrive

Ez a probléma leggyakrabban akkor fordul elő, amikor a felhasználó törli, és újra létrehozza a ugyanolyan egyszerű felhasználónév (UPN). Az új fiók jön létre egy másik értéket PUID (Passport egyedi azonosító) segítségével. Ha a felhasználó megpróbál hozzáférni egy webhelycsoport vagy a OneDrive, a felhasználó rendelkezik egy helytelen PUID. A második forgatókönyv magában foglalja a könyvtár szinkronizálás az Active Directory szervezeti egységet (OU). Ha a felhasználó rendelkezik már bejelentkezett a SharePoint, majd átkerül egy másik szervezeti egység és SharePoint resynced, akkor ez a probléma tapasztalhatnak.

A probléma megoldásához a cikk[az Office 365 rendszerben a felhasználó visszaállítási](https://docs.microsoft.com/office365/admin/add-users/restore-user?view=o365-worldwide)lépéseket az eredeti UPN kell visszaállítani.

Miután ez elkészült, a felhasználó rendelkezik rendszergazdai jogokat a OneDrive webhelyen történő [hozzáadása admin által a felhasználó OneDrive a](https://docs.microsoft.com/sharepoint/manage-user-profiles?redirectSourcePath=%252fen-us%252farticle%252fmanage-user-profiles-in-the-sharepoint-admin-center-494bec9c-6654-41f0-920f-f7f937ea9723#add-and-remove-admins-for-a-users-onedrive) lépéseket követve ellenőrizheti

Jogosultsági szintekkel kapcsolatos további tudnivalókért lásd a cikk [SharePoint jogosultsági szintek ismertetése](https://docs.microsoft.com/sharepoint/understanding-permission-levels).