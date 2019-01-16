---
title: 1336 RecoverableItems mappa megtelt
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: a3a923e8-fece-4a26-b8b6-00970d75275e
ms.openlocfilehash: ee96abfa179c36ebaf43dbd327d4608b849395d3
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: hu-HU
ms.lasthandoff: 01/15/2019
ms.locfileid: "28293507"
---
# <a name="the-recoverable-items-folder-is-full"></a>A helyreállítható elemek mappa megtelt.

A helyreállítható elemek mappa alapértelmezett tárolási korlátját az Office 365 rendszerben az Exchange Online postafiókok 30 GB. A helyreállítható elemek mappa tárolási korlátját automatikusan nő a 100 GB-os, amikor a postaláda helyezett per tartsa lenyomva tartás elektronikus adatok feltárása, vagy az Office 365 adatmegőrzési házirend hozzá van rendelve.
  
Ha a helyreállítható elemek mappa eléri a tárolási korlát, postafiók funkció hatással van a következő módon:
  
- A felhasználó az elemek nem törölhetők a postaládából.
    
- A kezelt Mappakezelő nem törölhető elemek adatmegőrzési címke vagy kezelt mappa beállításai alapján.
    
- A postafiókokhoz, vagy egyetlen elem helyreállítása engedélyezve van a Másolás írás közbeni lap védelem folyamatának a felhasználó által szerkeszthető elemek verziói nem tudja kezelni.
    
- -Postafiókok, amelyek rendelkeznek a postaláda-naplózás engedélyezve van postafiók napló bejegyzések a helyreállítható elemek mappában lévő eseményeket almappájába menti.
    
Nem mentesített postafiókok, rendszergazdák használhatják a `Search-Mailbox -SearchDumpsterOnly -DeleteContent` Exchange Online PowerShell a helyreállítható elemek mappa elemeinek törlése parancsot. További információt a következő témakörökben talál: 
  
- [Keresse meg és törölje a szükségtelen üzeneteket](https://docs.microsoft.com/office365/securitycompliance/search-for-and-delete-messagesadmin-help)
    
- [Keresés-postafiók](https://docs.microsoft.com/powershell/module/exchange/mailboxes/Search-Mailbox)
    
Visszatartott postafiókok rendszergazdák kell távolítsa el a mentesség, mielőtt azok a helyreállítható elemek mappából törölt elemek is. További tudnivalók: [törli az elemeket a helyreállítható elemek mappájában lévő felhőalapú postaládákba tartsa](https://docs.microsoft.com/en-us/office365/securitycompliance/delete-items-in-the-recoverable-items-folder-of-mailboxes-on-hold).
  
A helyreállítható elemek mappa teljes ne megelőzése érdekében rendszergazdák növelheti a helyreállítható elemek mappa postaládára tartsa, és állítsa be, hogy az elemek a helyreállítható elemek mappába helyez át a felhasználó archív postaláda adatmegőrzési tárolási korlátját a postafiókot. Lásd [a helyreállítható elemek tartsa postaládára vonatkozó kvóta növelése](https://docs.microsoft.com/office365/securitycompliance/increase-the-recoverable-quota-for-mailboxes-on-hold).
  
