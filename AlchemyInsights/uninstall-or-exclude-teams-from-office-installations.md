---
title: Az Office-telepítések eltávolítása vagy kizárása
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "2662"
- "9000660"
ms.openlocfilehash: 6fc5645028c9fb9df2606c0d03b67e87ae15087c
ms.sourcegitcommit: 1e5de64e34e9ba16185b3a895b3152ca61718f4b
ms.translationtype: MT
ms.contentlocale: hu-HU
ms.lasthandoff: 10/01/2019
ms.locfileid: "37344240"
---
# <a name="uninstall-or-exclude-teams-from-new-or-existing-office-installations"></a><span data-ttu-id="e0140-102">A csapatok eltávolítása vagy kizárása az új vagy meglévő Office-telepítésekből</span><span class="sxs-lookup"><span data-stu-id="e0140-102">Uninstall or exclude Teams from new or existing Office installations</span></span>

<span data-ttu-id="e0140-103">Mikroszkóp fuvaros van most tartalmazott részeként-ból Hivatal 365 ProPlus, Hivatal 365 teendő, és hivatal részére-fi.</span><span class="sxs-lookup"><span data-stu-id="e0140-103">Microsoft Teams is now included as part of Office 365 ProPlus, Office 365 Business, and Office for Mac.</span></span>

- <span data-ttu-id="e0140-104">Az [Office Deployment Tool](https://docs.microsoft.com/deployoffice/teams-install#how-to-exclude-microsoft-teams-from-new-installations-of-office-365-proplus) segítségével kizárhat csapatokat az Office új telepítésekből.</span><span class="sxs-lookup"><span data-stu-id="e0140-104">Use the [Office Deployment Tool](https://docs.microsoft.com/deployoffice/teams-install#how-to-exclude-microsoft-teams-from-new-installations-of-office-365-proplus) to exclude Teams from new installations of Office.</span></span>
- <span data-ttu-id="e0140-105">A csapatok *eltávolítása* a Windows operációs rendszert futtató eszközről: a [Microsoft csapatok eltávolítása](https://support.office.com/article/3b159754-3c26-4952-abe7-57d27f5f4c81).</span><span class="sxs-lookup"><span data-stu-id="e0140-105">To *uninstall* Teams from a device running Windows, see [Uninstall Microsoft Teams](https://support.office.com/article/3b159754-3c26-4952-abe7-57d27f5f4c81).</span></span> <span data-ttu-id="e0140-106">Ha a Microsoft teamet több célgépen vagy felhasználónál szeretné karbantartni, olvassa el a [Microsoft csapatok telepítésének tisztítása](https://docs.microsoft.com/microsoftteams/scripts/powershell-script-teams-deployment-clean-up)című témakört.</span><span class="sxs-lookup"><span data-stu-id="e0140-106">To clean up Microsoft Teams from multiple target machines or users, see [Microsoft Teams deployment clean up](https://docs.microsoft.com/microsoftteams/scripts/powershell-script-teams-deployment-clean-up).</span></span>
- <span data-ttu-id="e0140-107">Használja a [Preventteamsinstall](https://docs.microsoft.com/deployoffice/teams-install#use-group-policy-to-control-the-installation-of-microsoft-teams
) kapcsolót, hogy a Microsoft csapatok automatikusan telepíthetne az Office-ra.</span><span class="sxs-lookup"><span data-stu-id="e0140-107">Use the [PreventTeamsInstall](https://docs.microsoft.com/deployoffice/teams-install#use-group-policy-to-control-the-installation-of-microsoft-teams
) option to prevent Microsoft Teams from installing automatically with Office.</span></span>
- <span data-ttu-id="e0140-108">A [megelőző Firstlaunchafterinstall](https://docs.microsoft.com/deployoffice/teams-install#use-group-policy-to-prevent-microsoft-teams-from-starting-automatically-after-installation) beállítás használata a *csapatok telepítése előtt*annak megakadályozására, hogy a Microsoft csapatok a telepítés után automatikusan elindulnak.</span><span class="sxs-lookup"><span data-stu-id="e0140-108">Use the [PreventFirstLaunchAfterInstall](https://docs.microsoft.com/deployoffice/teams-install#use-group-policy-to-prevent-microsoft-teams-from-starting-automatically-after-installation) option, *before Teams is installed*, to prevent Microsoft Teams from starting automatically after installation.</span></span>

<span data-ttu-id="e0140-109">Ha az Office for Mac programot használja, tekintse [meg a Microsoft csapatok telepítéseit Macintosh gépen](https://docs.microsoft.com/deployoffice/teams-install#microsoft-teams-installations-on-a-mac).</span><span class="sxs-lookup"><span data-stu-id="e0140-109">If you're using Office for Mac, see [Microsoft Teams installations on a Mac](https://docs.microsoft.com/deployoffice/teams-install#microsoft-teams-installations-on-a-mac).</span></span>