---
title: 1048 5.7.750 szolgáltatás nem érhető el. Blokkolja a nem regisztrált tartományokból küldött ügyfél
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 9/28/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 8cf6d70b-9a78-4f04-ac59-7ffcf44ffd22
ms.custom: 1048
ms.openlocfilehash: 5eb42679f123fcd1b680327329721cb47e18e11a
ms.sourcegitcommit: 03a156a9c9740521155a30775492c7dff0982588
ms.translationtype: MT
ms.contentlocale: hu-HU
ms.lasthandoff: 03/22/2019
ms.locfileid: "30776504"
---
# <a name="57750-client-blocked-from-sending-from-unregistered-domain"></a><span data-ttu-id="7ddb8-103">5.7.750 ügyfél a küldő nem regisztrált tartomány zárolva</span><span class="sxs-lookup"><span data-stu-id="7ddb8-103">5.7.750 Client blocked from sending from unregistered domain</span></span>

<span data-ttu-id="7ddb8-104">A hiba akkor fordul elő, amikor egy nagy mennyiségű üzenetet küldött, amely nem az Office 365 rendszerben (adódnak, elfogadott tartományok és érvényesített) kiépítése tartományokból.</span><span class="sxs-lookup"><span data-stu-id="7ddb8-104">The error occurs when a large volume of messages are sent from domains that aren't provisioned in Office 365 (added as accepted domains and validated).</span></span>
  
<span data-ttu-id="7ddb8-105">A hiba elkerülése érdekében használhatja, ha a tanúsítványt tartományi kiépítése tartomány, vagy lehet kiépíteni a küldő tartomány összes tanúsítvány-alapú levelezési folyamat összekötő.</span><span class="sxs-lookup"><span data-stu-id="7ddb8-105">To avoid this error, you can use a certificate-based mail flow connector where the certificate's domain is a provisioned domain, or you can provision all sending domains.</span></span>
  
