---
title: SharePoint Online PowerShell
ms.author: v-todmc
author: todmccoy
manager: mnirkhe
ms.date: 9/18/19
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000266"
- "1867"
ms.openlocfilehash: 00ec337ce34da9d3c3fba0a71602c3078a556552
ms.sourcegitcommit: 6b102e079a7d30298105fd811a67efb707d6d5bf
ms.translationtype: MT
ms.contentlocale: hu-HU
ms.lasthandoff: 09/23/2019
ms.locfileid: "37123001"
---
# <a name="sharepoint-online-powershell"></a><span data-ttu-id="a4235-102">SharePoint Online PowerShell</span><span class="sxs-lookup"><span data-stu-id="a4235-102">Sharepoint Online PowerShell</span></span>

<span data-ttu-id="a4235-103">Munka PowerShell vagy szkriptek belül SharePoint Online?</span><span class="sxs-lookup"><span data-stu-id="a4235-103">Working with PowerShell or Scripts within Sharepoint Online?</span></span> <span data-ttu-id="a4235-104">További információért látogasson el az alábbi linkekre.</span><span class="sxs-lookup"><span data-stu-id="a4235-104">Visit the links below for more information.</span></span>
- [<span data-ttu-id="a4235-105">Ismerkedés a SharePoint Online Management Shell alkalmazással</span><span class="sxs-lookup"><span data-stu-id="a4235-105">Getting started with SharePoint Online Management Shell</span></span>](https://docs.microsoft.com/powershell/sharepoint/sharepoint-online/connect-sharepoint-online?view=sharepoint-ps)
- [<span data-ttu-id="a4235-106">Csatlakozás az SPO PowerShell rendszerhez többtényezős hitelesítéssel (MFA)</span><span class="sxs-lookup"><span data-stu-id="a4235-106">Connect to SPO PowerShell with multifactor authentication (MFA)</span></span>](https://docs.microsoft.com/powershell/sharepoint/sharepoint-online/connect-sharepoint-online?view=sharepoint-ps#to-connect-with-multifactor-authentication-mfa)
- <span data-ttu-id="a4235-107">A [SharePoint-minták és-gyakorlatok (PNP)](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps) a PowerShell parancsok olyan könyvtárát tartalmazzák, amely lehetővé teszi az spo felé irányuló összetett kezelési műveletek végrehajtását.</span><span class="sxs-lookup"><span data-stu-id="a4235-107">[SharePoint Patterns and Practices (PnP)](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps) contains a library of PowerShell commands that allows you to perform complex management actions towards SPO.</span></span>

> [!NOTE]
> - <span data-ttu-id="a4235-108">Ha ön birtoklás kérdés összekötő pálca-val a SPO vezetés gránát, győződj meg amit önnek van korszerűsített-hoz legutolsó változat és megpróbál [-hoz ré hang-behoz a elem](https://docs.microsoft.com/powershell/developer/module/importing-a-powershell-module) használ *"behoz-elem Mikroszkóp. online. SharePoint. PowerShell".*</span><span class="sxs-lookup"><span data-stu-id="a4235-108">If you are having issues connecting with the SPO management shell, make sure that you have updated to the latest version and try to [re-import the module](https://docs.microsoft.com/powershell/developer/module/importing-a-powershell-module) using *“Import-Module Microsoft.Online.SharePoint.PowerShell”.*</span></span>
> - <span data-ttu-id="a4235-109">Ha ügyféloldali objektummodell-parancsfájlok futtatását kísérli meg, a [SharePoint Online ügyfél-összetevők SDK csomagot](https://www.microsoft.com/download/details.aspx?id=42038) kell telepítenie a helyi számítógépre.</span><span class="sxs-lookup"><span data-stu-id="a4235-109">If you are attempting to run client-side object model scripts, you will need to have the [Sharepoint Online Client Components SDK](https://www.microsoft.com/download/details.aspx?id=42038) installed on your local machine.</span></span>
> - <span data-ttu-id="a4235-110">Ha probléma van a PowerShell parancsfájlokkal, akkor érdemes megfontolni a PowerShell futtatását rendszergazdaként és a [végrehajtási házirend](https://docs.microsoft.com/powershell/module/microsoft.powershell.core/about/about_execution_policies?view=powershell-6)módosításával.</span><span class="sxs-lookup"><span data-stu-id="a4235-110">If you are having issues running scripts from PowerShell, you may want to consider running PowerShell as an Administrator and changing the [Execution Policy](https://docs.microsoft.com/powershell/module/microsoft.powershell.core/about/about_execution_policies?view=powershell-6).</span></span>