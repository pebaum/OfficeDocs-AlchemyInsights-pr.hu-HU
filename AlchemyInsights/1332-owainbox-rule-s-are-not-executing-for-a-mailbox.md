---
title: 1332 OWA - Beérkezett üzenetek szabály(ok) nem végrehajtása postafiókhoz
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 12/8/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 383d1c77-5e4b-4a69-92d6-c404d890b6b7
ms.openlocfilehash: f090d0a9d84bc6a4d1a1f4c0af55102d4b0ddfbe
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: hu-HU
ms.lasthandoff: 01/15/2019
ms.locfileid: "28294005"
---
# <a name="an-inbox-rule-doesnt-work-as-expected"></a>A Beérkezett üzenetek szabály nem a várt módon működik

Ellenőrizze az alábbi beállításokat:
  
- Egy üzenet átirányíthatók, továbbított vagy automatikusan a Beérkezett üzenetekre vonatkozó szabályok alapján csak egy alkalommal a válaszok. Átirányíthatja a legitim forrásból szabály (szabály a Beérkezett üzenetek vagy mail Attribútumfolyam-szabály, más néven átviteli szabály) legfeljebb tíz továbbítás címzett üzenetet adhat. További tudnivalókért lásd: [napló, a szállítás, és a Beérkezett üzenetek szabály korlátai](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits).
    
- A másodlagos naplózási postaláda Beérkezett üzenetekre vonatkozó szabályok nem működnek. További információt az alternatív naplózási postaláda lásd: [alternatív naplózási postaláda](https://docs.microsoft.com/Exchange/security-and-compliance/journaling/journaling#alternate-journaling-mailbox).
    
Ezek a problémák megoldásához, lásd: [KB 2829319](https://support.microsoft.com/kb/2829319).
  
A fenti hibákat nem alkalmazza, ha a Beérkezett üzenetek szabály diagnosztikai jelentés futtatása, mielőtt segítséget kér a probléma a Microsoft Support:
  
1. A postaláda megnyitása az Outlook alkalmazásban a weben, és kattintson a **Beállítások** \> **Beállítások** \> **Rendezés e-mail** \> **Beérkezett üzenetekre vonatkozó szabályok**.
    
2. A lap alján kattintson, **Ha a szabályok nem működnek a diagnosztikai jelentés létrehozásához kattintson ide**.
    
