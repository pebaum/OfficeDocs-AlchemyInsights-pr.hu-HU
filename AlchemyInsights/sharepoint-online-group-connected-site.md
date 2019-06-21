---
title: Csoport hozzáadása egy SharePoint-webhely
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: f7d730bf-0d6e-424c-970c-6137c71cb50b
ms.openlocfilehash: f0126f7f753275e9bbf8c3a09a6af5faf9a27862
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: hu-HU
ms.lasthandoff: 06/07/2019
ms.locfileid: "34758733"
---
# <a name="create-group-connected-site-in-sharepoint-online"></a>A SharePoint Online kapcsolattal rendelkező hely csoport létrehozása

Van néhány általános problémát észlelt létrehozása, vagy hozza létre újra a csoport webhely kapcsolat.

 Ha törölt egy csoport és a kapcsolódó webhely, és létrehoz egy másik webhely ugyanazt az URL-címmel, szüksége lesz a végleges eltávolítása az előző webhelyhez.

[Sao felügyeleti rendszerhéj](https://support.office.com/article/introduction-to-the-sharepoint-online-management-shell-c16941c3-19b4-4710-8056-34c034493429) letöltése

 További információ a Bevezetés a powershell lásd: [Bevezetés a SharePoint Online felügyeleti rendszerhéj](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite?view=sharepoint-ps)

Távolítsa el a webhely törölt helyek az [Eltávolítás-SPODeletedSite](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite?view=sharepoint-ps) powershell parancsmag használatával.

Ha készítünk egy csoport kapcsolattal rendelkező hely, és már létezik egy másik csoportot ugyanazzal az aliasnévvel rendelkező figyelmeztetést kap, ellenőrizze az [Office 365 felügyeleti központból a](https://admin.microsoft.com/Adminportal/Home?source=applauncher#/groups)meglévő csoportjait. A probléma megoldásához, törli a meglévő csoportot, ha már nincs szüksége, vagy hozzon létre egy másikat a webhely kap.

Különböző módon lehet létrehozni és modern csoportok használata a SharePoint.

Az Office 365 csoport meglévő webhelyekhez csatlakozhat. További információért lásd: [Csatlakozás az Office 365 csoport segítségével a SharePoint felhasználói ineterface](https://docs.microsoft.com/sharepoint/dev/transform/modernize-connect-to-office365-group#connect-an-office-365-group-using-the-sharepoint-user-interface).

Az Office 365 csoport kapcsolattal rendelkező hely létrehozásához szüksége lesz a csoportwebhely létrehozása. További információért lásd: [Create a SharePoint csoportwebhelyet](https://support.office.com/article/create-a-team-site-in-sharepoint-ef10c1e7-15f3-42a3-98aa-b5972711777d).
