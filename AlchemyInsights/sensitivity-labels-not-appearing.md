---
title: Nem megjelenő érzékenységi címkék
ms.author: pebaum
author: pebaum
manager: laurawi
ms.date: 04/21/2020
ms.audience: admin
ms.topic: article
ms.prod: office-online-server
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1778"
- "9000181"
ms.openlocfilehash: 1326eca02044014a8e9c072fcc3e4cd3a41c7a9f
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: hu-HU
ms.lasthandoff: 06/02/2020
ms.locfileid: "44511654"
---
# <a name="sensitivity-labels-not-appearing"></a>Nem megjelenő érzékenységi címkék

Az érzékenységi címkék lehetővé teszik az érzékeny tartalmak osztályozását és védelmét. Ezek a Microsoft 365 megfelelőségi központban, a Microsoft 365 biztonsági központban vagy a Microsoft 365 biztonsági & megfelelőségi központban hozhatók létre a Besorolási > az érzékenységi címkék alatt. A funkcióról az [Érzékenységi címkék áttekintése című témakörben olvashat bővebben.](https://docs.microsoft.com/microsoft-365/compliance/sensitivity-labels)

Ha konfigurálta az érzékenységi címkéket, de azok nem jelennek meg az Office-alkalmazásokban, ellenőrizze az alábbiakat:

- Ellenőrizze, hogy az érzékenységi címke [közzé lett-e téve](https://docs.microsoft.com/microsoft-365/compliance/sensitivity-labels#what-label-policies-can-do) a kívánt felhasználók és csoportok számára.

- Ellenőrizze, hogy a felhasználó olyan alkalmazást használ-e, amely támogatja az érzékenységi címkéket – tekintse meg [az érzékenységi címkéket a dokumentumban.](https://support.office.com/article/apply-sensitivity-labels-to-your-documents-and-email-within-office-2f96e7cd-d5a4-403b-8bd7-4cc636bae0f9?#bkmk_whereavailable)

- Ha az [Azure Information Protection címkéket telepíti át,](https://docs.microsoft.com/azure/information-protection/configure-policy-migrate-labels)vegye figyelembe az [itt](https://docs.microsoft.com/azure/information-protection/configure-policy-migrate-labels#considerations-for-unified-labels)felsorolt szempontokat.

- Adatveszteség-megelőzési (DLP) támogatás: Jelenleg csak a megőrzési címkék használhatók feltételként a DLP-házirendekben.  A DLP-házirendben az érzékenységi címkék támogatása még nem érhető el, de dolgozunk rajta.

- Ha a titkosítás engedélyezve van egy érzékenységi címkén, a következő t választhatja:
    - Engedélyek hozzárendelése most
    - Engedélyek hozzárendelésének lehetővé teszi a felhasználók számára


A lehetséges problémákról az [Ismert érzékenységi címkékkel kapcsolatos tudnivalók](https://support.office.com/article/known-issues-with-sensitivity-labels-in-office-b169d687-2bbd-4e21-a440-7da1b2743edc)című témakörben talál további információt.