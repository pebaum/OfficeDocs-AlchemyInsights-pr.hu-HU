---
title: Nem lehet hozzáadni a jóváhagyási munkafolyamat 2010
ms.author: kirks
author: Techwriter40
ms.date: 12/3/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 0df65cf9-7eae-4de7-88e9-1914635c8d11
ms.openlocfilehash: a83a9621ca0f7764d3f2c0a698dbffd80d55e80c
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: hu-HU
ms.lasthandoff: 01/15/2019
ms.locfileid: "28294313"
---
# <a name="unable-to-add-2010-approval-workflow"></a>Nem lehet hozzáadni a jóváhagyási munkafolyamat 2010

A Microsoft SharePoint-webhelycsoport nem adhat (például a "Jóváhagyás – SharePoint 2010") globálisan újrafelhasználható munkafolyamat listához vagy könyvtárhoz.
  
A probléma megoldásához kövesse az alábbi lépéseket: 
  
1. Nyissa meg a legfelső szintű webhely helycsoport a SharePoint Designer 2013.
  
2. **A helyobjektumok**jelölje be a **munkafolyamatok**. 
  
3. A **munkafolyamatok** menüszalag **Új** csoportjában jelölje be **Újrahasználható munkafolyamat**. 
  
4. Az **Újrahasználható munkafolyamat létrehozása** űrlapon adja meg a nevét ** *Repair2010* **. **Platform típusát**kattintson a **SharePoint 2010 munkafolyamat**, és kattintson az **OK gombra**. 
  
1. A **munkafolyamat** -menüszalag **mentése** csoportjában jelölje be **a közzététel**. 
  
2. A **munkafolyamat** -menüszalag **kezelése** csoportjában válassza **Globálisan közzétenni**. A megjelenő megerősítést kérő párbeszédpanelen kattintson az **OK gombra**. 
  
3. Egy webböngészőben keresse meg a legfelső szintű webhely helycsoport, és hozzáférhet a **Webhely beállításai** \> **Webhelycsoport-szolgáltatások**. Váltás a **munkafolyamatok** szolgáltatás: 
  
· Ha a szolgáltatás *aktív* , kattintson az **Inaktiválás,** és kattintson az **Aktiválás**. 
  
· Ha a szolgáltatás *inaktívvá válnak* , kattintson az **Aktiválás**. 
  
További információt találhat a következő [cikk](https://go.microsoft.com/fwlink/?linkid=2047770&amp;clcid=0x409).
  
