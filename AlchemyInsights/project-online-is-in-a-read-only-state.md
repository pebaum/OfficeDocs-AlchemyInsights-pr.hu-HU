---
title: A Project Online írásvédett állapotban van
ms.author: pebaum
author: pebaum
manager: pamg
ms.date: 4/10/2019
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "1776"
- "9000205"
ms.openlocfilehash: 34fecf93f39659cbd26998697090957c6af45aa0
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: hu-HU
ms.lasthandoff: 12/15/2019
ms.locfileid: "41969515"
---
# <a name="project-online-is-in-a-read-only-state"></a><span data-ttu-id="049d0-102">A Project Online írásvédett állapotban van</span><span class="sxs-lookup"><span data-stu-id="049d0-102">Project Online is in a read-only state</span></span>

<span data-ttu-id="049d0-103">A Project Online három gyakori oka lehet annak, hogy a Project Online csak olvasható állapotba kerül:</span><span class="sxs-lookup"><span data-stu-id="049d0-103">There are three common reasons why Project Online may reach a read-only state:</span></span>

1. <span data-ttu-id="049d0-104">A szervezetek csak Project Online Essentials licenccel rendelkeznek.</span><span class="sxs-lookup"><span data-stu-id="049d0-104">Organizations have a Project Online Essentials license(s) only.</span></span> <span data-ttu-id="049d0-105">Ez nem elég ahhoz, hogy életben tartsa a webhelyet, és végül de-provisioned.</span><span class="sxs-lookup"><span data-stu-id="049d0-105">This isn't enough to keep the site alive and it will eventually get de-provisioned.</span></span><span data-ttu-id="049d0-106">Az oldalt csak olvasható állapotba helyezzük, hogy az adminisztrátorok tudják, hogy valami nincs rendben, és megszerezhessék a megfelelő licenceket.</span><span class="sxs-lookup"><span data-stu-id="049d0-106"> We place the site in a read-only state so that Admins know something is wrong and can acquire the correct licenses.</span></span> <span data-ttu-id="049d0-107">A rendszergazdáknak hozzá kell adniuk egy Project Online Professional és/vagy Premium licencet.</span><span class="sxs-lookup"><span data-stu-id="049d0-107">Admins will need to add a Project Online Professional and/or Premium license.</span></span> <span data-ttu-id="049d0-108">Az oldal jön ki az írásvédett ezen a ponton.</span><span class="sxs-lookup"><span data-stu-id="049d0-108">The site will come out of read-only at that point.</span></span> <span data-ttu-id="049d0-109">További információ: [Projektkezelési megoldások összehasonlítása](https://products.office.com/project/compare-microsoft-project-management-software?tab=1).</span><span class="sxs-lookup"><span data-stu-id="049d0-109">For more info, see [Compare Project Management Solutions](https://products.office.com/project/compare-microsoft-project-management-software?tab=1).</span></span>
2. <span data-ttu-id="049d0-110">Elérte a hozzárendelt kvótát.</span><span class="sxs-lookup"><span data-stu-id="049d0-110">Assigned quota has been reached.</span></span> <span data-ttu-id="049d0-111">További információ: [Project Web App Quota](https://docs.microsoft.com/projectonline/tune-project-online-performance#project-web-app-quota).</span><span class="sxs-lookup"><span data-stu-id="049d0-111">For more info, see [Project Web App Quota](https://docs.microsoft.com/projectonline/tune-project-online-performance#project-web-app-quota).</span></span> <span data-ttu-id="049d0-112">Ellenőrizze: [Az időfázisos jelentési adatok összesítésének konfigurálása a Project Online-ban,](https://docs.microsoft.com/ProjectOnline/configure-rollup-of-timephased-reporting-data-in-project-online?redirectSourcePath=%252fen-us%252farticle%252fConfigure-rollup-of-timephased-reporting-data-in-Project-Online-da8487fe-899e-4510-a264-e2ebc948928c) és megtudhatja, hogy a jelentéskészítés részletessége milyen hatással lehet a kvótahasználatra.</span><span class="sxs-lookup"><span data-stu-id="049d0-112">Check [Configure rollup of timephased reporting data in Project Online](https://docs.microsoft.com/ProjectOnline/configure-rollup-of-timephased-reporting-data-in-project-online?redirectSourcePath=%252fen-us%252farticle%252fConfigure-rollup-of-timephased-reporting-data-in-Project-Online-da8487fe-899e-4510-a264-e2ebc948928c) to see how reporting granularity may impact quota usage.</span></span>
3. <span data-ttu-id="049d0-113">A csak olvasható állapot nagyon átmeneti állapot lehet, amely a karbantartás során fordulhat elő.</span><span class="sxs-lookup"><span data-stu-id="049d0-113">Read-only can be a very temporary condition that can occur during maintenance.</span></span> <span data-ttu-id="049d0-114">A legtöbb karbantartást nem is veszik észre ügyfeleink, és nem fogja gyakran látni ezt, de vannak esetek, amikor rövid ideig csak olvasható tapasztalható.</span><span class="sxs-lookup"><span data-stu-id="049d0-114">Most maintenance is not even noticed by our customers and you will not often see this, but there are times when short periods of read-only are experienced.</span></span>