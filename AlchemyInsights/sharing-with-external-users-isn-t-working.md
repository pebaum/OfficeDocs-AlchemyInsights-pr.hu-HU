---
title: Nem működik a megosztás külső felhasználókkal
ms.author: mikeplum
author: MikePlumleyMSFT
manager: scotv
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: d3d0b69b-214e-4859-8957-621fd6306b30
ms.openlocfilehash: 37da77c73b3abbdcf9cb2b9c4c43f31eea3c0a49
ms.sourcegitcommit: 286000b588adef1bbbb28337a9d9e087ec783fa2
ms.translationtype: MT
ms.contentlocale: hu-HU
ms.lasthandoff: 04/27/2020
ms.locfileid: "43913004"
---
# <a name="fix-problems-sharing-sharepoint-content-with-external-users"></a>A SharePoint-tartalmak külső felhasználókkal való megosztásával kapcsolatos problémák megoldása

Győződjön meg arról, hogy a külső megosztás be van kapcsolva a szervezetnél:
  
1. Nyissa meg a [Microsoft 365 Felügyeleti központ &amp; Szolgáltatások bővítményeit tartalmazó lapot,](https://portal.office.com/adminportal/home#/Settings/ServicesAndAddIns)és kattintson a Webhelyek **gombra.**
    
2. Ellenőrizze, hogy a beállítás be van-e kapcsolva. Ha a "Csak a meglévő külső felhasználók" jelölőnégyzet be van jelölve, ellenőrizze, hogy a külső felhasználó szerepel-e a Microsoft 365 Felügyeleti központban.
    
Győződjön meg arról, hogy a külső megosztás be van kapcsolva a webhelyen. Klasszikus webhelycsoport esetén:
  
1. Az új SharePoint Felügyeleti központban, a bal oldali ablaktáblában kattintson a **Webhelyek**elemre.
    
2. Jelölje ki a webhelyet vagy webhelyeket, és a menüszalagon kattintson a **Megosztás gombra.**
    
Microsoft 365-csoporthoz vagy kommunikációs webhelyhez tartozó csoportwebhely esetén:
  
- Ezek az új webhelytípusok ugyanazt a megosztási beállítást, mint a szervezeti szintű beállítás, kivéve, ha a szervezeti szintű beállítás lehetővé teszi a fájlok megosztását olyan hivatkozások használatával, amelyek nem igényelnek bejelentkezést. Ebben az esetben a webhelyek lehetővé teszik a megosztást a bejelentkező új és meglévő külső felhasználókkal. Adott webhelyek beállításának módosításához használja az új SharePoint Felügyeleti központot vagy a PowerShellt. [További információ](https://go.microsoft.com/fwlink/?linkid=871863).
    
> [!NOTE]
> A külső megosztási beállítás bármely webhelyesetében szigorúbb lehet, mint a szervezeti szintű beállítás, de nem lehet megengedőbb, mint a szervezeti szintű beállítás. 
  

