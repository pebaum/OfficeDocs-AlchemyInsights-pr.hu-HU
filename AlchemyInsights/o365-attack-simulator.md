---
title: 2681 Támadás szimulátor a Microsoft 365-ben
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "2681"
ms.assetid: ''
ms.openlocfilehash: 3dae4768ca62757ce7f92dfc527078c963d72742
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: hu-HU
ms.lasthandoff: 06/02/2020
ms.locfileid: "44506740"
---
# <a name="attack-simulator-in-microsoft-365"></a>Támadás szimulátor a Microsoft 365

- Hiányzik támadás szimulátor? A Támadásszimulátor használatához az **Office 365 Komplex veszélyforrások elleni védelem 2.** **Office 365 Enterprise E5** Az Attack Simulator **nem** része az Office 365 Komplex veszélyforrások elleni védelem 1., 1.

- A szimulált támadások indításához használt fiókhoz globális rendszergazdai vagy biztonsági rendszergazdai engedélyekés többtényezős hitelesítés (MFA) szükséges. Az Attack Simulator követelményeiről a [jelen témakörben](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator)olvashat bővebben.

- Fontos tudnivalók a **Brute Force Password** támadásszimulációiról:

  - Ha a célfiókban engedélyezve van az MFA, és a jelszó helyesen lett kitalálva, a fiók nem jelenik meg feltörtként (a második hitelesítési tényező nem lesz teljes).

  - A jelszófájl nem lehet nagyobb 10 MB-nál. Soronként egy jelszót használjon, és a lista utolsó jelszava után adjon meg egy üres sort (kocsivissza).

- Fontos tudnivalók a **spear phishing** csatolásáról szimulációk:

  - Az **adathalászat-kiszolgáló URL-címéhez**nem adhat meg egyéni értéket.

  - Ha a címzett [a Jelentésüzenet engedélyezése bővítményt](https://docs.microsoft.com/microsoft-365/security/office-365-security/enable-the-report-message-add-in) használja az üzenet adathalászatként való jelentéséhez, előfordulhat, hogy nem kap értesítést az üzenetről (mivel ez egy szimulált támadás).

- Jelentések: A szimulált támadás befejezése után a **támadás részletei** gombra kattintva megtekintheti a jelentést.

- Az Attack Simulator részletes útmutatásait és új funkcióit a [Microsoft 365 Támadásszimulátor című témakörében találja.](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator)
