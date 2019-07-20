---
title: Dynamics 365 képezi az üzleti szabályok - üzleti szabály nem Firing-űrlap
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1926"
- "6200018"
ms.openlocfilehash: 4ade8d2f68b465298e2d6efff3eef4f04f25c3bf
ms.sourcegitcommit: a413a0e27ef4ab8c484fa9fccff8bbef381c8b96
ms.translationtype: MT
ms.contentlocale: hu-HU
ms.lasthandoff: 07/16/2019
ms.locfileid: "35747853"
---
# <a name="onchange-event-does-not-occur-if-the-field-is-changed-programmatically"></a>Módosításra esemény fordul elő, ha a mező módosul programozott

A *módosításra* esemény fordul elő, ha a mező módosul a programozás útján használja a *attribútum.* [Értékbeállítás](https://docs.microsoft.com/en-us/dynamics365/customer-engagement/developer/clientapi/reference/attributes/setvalue) módszer. Ha azt szeretné futtatni kell használni az érték beállítása után a *módosításra* esemény eseménykezelők a *attribútum formContext.data.entity.* [fireOnchange](https://docs.microsoft.com/en-us/dynamics365/customer-engagement/developer/clientapi/reference/attributes/fireonchange) módszer a kódban.

[https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/events/attribute-onchange](https://docs.microsoft.com/en-us/dynamics365/customer-engagement/developer/clientapi/reference/events/attribute-onchange)