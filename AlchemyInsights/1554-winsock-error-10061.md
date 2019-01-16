---
title: 1554 Winsock hiba 10061
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 12/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: caecfa19-86c9-4aa4-9c83-b8a974ce60b9
ms.openlocfilehash: 96a9cfd11941158ddf13655c74974e3eb800e570
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: hu-HU
ms.lasthandoff: 01/15/2019
ms.locfileid: "28293366"
---
# <a name="winsock-error-10061"></a>Winsock hiba 10061

Ez a hibakód azt jelenti, hogy Office 365 nem tudta létrehozni a TCP-szoftvercsatornát (kapcsolat) és a célállomás. A hiba legvalószínűbb oka a tűzfal konfigurációs probléma. A probléma megoldásához ellenőrizze ezeket a beállításokat:
  
- Az [Office 365 URL-címek és IP-címtartományokat](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges) adatokkal a tűzfal konfigurációjának ellenőrzése
    
- A hiba esetén az Exchange Online Protection (EOP) adott kell korábban értesítést kapott a módosítása az [Exchange Online védelem IP-címeket](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).
    
- Győződjön meg arról, hogy az internetszolgáltató (ISP) nem blokkolja azt a portot.
    
- Ellenőrizze az intelligens állomás és a cél kiszolgáló beállításai az összekötők.
    
Fontos megjegyezni, hogy Office 365 nem blokkolja a *bejövő* kapcsolatok ily módon. 
  
