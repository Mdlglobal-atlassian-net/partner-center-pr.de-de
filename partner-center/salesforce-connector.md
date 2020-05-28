---
title: Der Co-Selling-Connector für das Salesforce CRM Partner Center
ms.topic: article
ms.date: 05/22/2020
ms.service: partner-dashboard
ms.subservice: partnercenter-csp
description: Verwenden Sie den Salesforce CRM-Connector, um Verweise von Microsoft zu erhalten.
ms.assetid: c6fca2c0-2e6c-41b1-9be8-b363b139f15b
author: LauraBrenner
ms.author: labrenne
keywords: ''
ms.localizationpriority: medium
ms.openlocfilehash: ad39bdde92611066d0dd0c56d8b9133f4d9dcaa9
ms.sourcegitcommit: 97f1ff7386562cbb945bdfbcf15c85bc8303cac2
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/25/2020
ms.locfileid: "83825697"
---
# <a name="co-sell-connector-for-salesforce-crm---overview"></a><span data-ttu-id="47702-103">Co-Selling-Connector für Salesforce CRM-Übersicht</span><span class="sxs-lookup"><span data-stu-id="47702-103">Co-sell connector for Salesforce CRM - overview</span></span>

### <a name="appropriate-roles"></a><span data-ttu-id="47702-104">Geeignete Rollen</span><span class="sxs-lookup"><span data-stu-id="47702-104">Appropriate roles</span></span>

- <span data-ttu-id="47702-105">Empfehlungsadministrator</span><span class="sxs-lookup"><span data-stu-id="47702-105">Referrals admin</span></span>
- <span data-ttu-id="47702-106">Systemadministrator oder systemanpassungsprogramm im CRM</span><span class="sxs-lookup"><span data-stu-id="47702-106">System admin or system customizer on the CRM</span></span>

<span data-ttu-id="47702-107">Der Partner Center-Co-Selling-Connector ermöglicht ihren Verkäufern das Co-Selling mit Microsoft innerhalb Ihrer CRM-Systeme.</span><span class="sxs-lookup"><span data-stu-id="47702-107">Partner Center co-sell connector enables your sellers to co-sell with Microsoft from within your CRM systems.</span></span> <span data-ttu-id="47702-108">Sie müssen nicht für die Verwendung von Partner Center zur Verwaltung von Co-Selling-Geschäften geschult werden.</span><span class="sxs-lookup"><span data-stu-id="47702-108">They won’t have to be trained to use Partner Center to manage Co-sell deals.</span></span> <span data-ttu-id="47702-109">Mithilfe der Co-Selling-Connectors können Sie einen neuen Co-Selling-Verweis zum Einbinden eines Microsoft-Verkäufers erstellen, Referenzen vom Microsoft-Verkäufer erhalten, Verweise akzeptieren/ablehnen, Geschäftsdaten ändern, wie z. b. den Geschäftswert, das Enddatum usw. und alle Updates von den Microsoft-Verkäufern für diese Co-Selling-Angebote erhalten.</span><span class="sxs-lookup"><span data-stu-id="47702-109">Using the Co-sell connectors, you will be able to create a new Co-sell referral to engage a Microsoft seller, receive referrals from the Microsoft seller, accept/decline referrals, modify deal data such as deal value, closing date etc. as well as receive any updates from the Microsoft sellers on these Co-sell deals.</span></span> <span data-ttu-id="47702-110">Sie können all dies tun, während Sie im CRM Ihrer Wahl arbeiten und nicht im Partner Center.</span><span class="sxs-lookup"><span data-stu-id="47702-110">You can do all of this while working within the CRM of your choice rather than in Partner Center.</span></span> 

<span data-ttu-id="47702-111">Die Lösung basiert auf der Microsoft Power automatisieren-Lösung und verwendet die Microsoft Partner Center-APIs.</span><span class="sxs-lookup"><span data-stu-id="47702-111">The solution is based on Microsoft Power Automate Solution and uses Microsoft Partner Center APIs.</span></span>


## <a name="before-you-install---pre-requisites"></a><span data-ttu-id="47702-112">Vor der Installation von-Pre-Requirements</span><span class="sxs-lookup"><span data-stu-id="47702-112">Before you install - pre-requisites</span></span>

|<span data-ttu-id="47702-113">**Themen**</span><span class="sxs-lookup"><span data-stu-id="47702-113">**Topics**</span></span>   |<span data-ttu-id="47702-114">**Details**</span><span class="sxs-lookup"><span data-stu-id="47702-114">**Details**</span></span>   |<span data-ttu-id="47702-115">**Links**</span><span class="sxs-lookup"><span data-stu-id="47702-115">**Links**</span></span>   |
|--------------|--------------------|------|
|<span data-ttu-id="47702-116">Microsoft Partner Network-ID</span><span class="sxs-lookup"><span data-stu-id="47702-116">Microsoft Partner Network ID</span></span> |<span data-ttu-id="47702-117">Sie benötigen eine gültige MPN-ID.</span><span class="sxs-lookup"><span data-stu-id="47702-117">You need a valid MPN ID</span></span>|<span data-ttu-id="47702-118">So fügen Sie [MPN](https://partner.microsoft.com/) an</span><span class="sxs-lookup"><span data-stu-id="47702-118">To join [MPN](https://partner.microsoft.com/)</span></span>|
|<span data-ttu-id="47702-119">Co-Selling bereit</span><span class="sxs-lookup"><span data-stu-id="47702-119">Co-sell ready</span></span>|<span data-ttu-id="47702-120">Ihre IP-/Dienst-Lösung muss für den Co-Selling bereit sein.</span><span class="sxs-lookup"><span data-stu-id="47702-120">Your IP/Services solution must be co-sell ready.</span></span>|[<span data-ttu-id="47702-121">Vertrieb mit Microsoft</span><span class="sxs-lookup"><span data-stu-id="47702-121">Sell with Microsoft</span></span>](https://partner.microsoft.com/membership/sell-with-microsoft)| 
|<span data-ttu-id="47702-122">Partner Center-Konto</span><span class="sxs-lookup"><span data-stu-id="47702-122">Partner Center account</span></span>|<span data-ttu-id="47702-123">Die MPN-ID, die dem Partner Center-Mandanten zugeordnet ist, muss mit der MPN-ID identisch sein, die ihrer Co-Selling-Lösung zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="47702-123">The MPN ID associated with the Partner Center tenant must be same as the MPN ID associated with your Co-sell solution.</span></span> <span data-ttu-id="47702-124">Vergewissern Sie sich, dass Sie Ihre Co-Selling-Verweise im Partner Center-Portal sehen können, bevor Sie die Connectors bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="47702-124">Verify that you can see your co-sell referrals in Partner Center portal prior to deploying the connectors.</span></span>|[<span data-ttu-id="47702-125">Verwalten Ihres Kontos</span><span class="sxs-lookup"><span data-stu-id="47702-125">Manage your account</span></span>](create-user-accounts-and-set-permissions.md)|
|<span data-ttu-id="47702-126">Partner Center-Benutzerrollen</span><span class="sxs-lookup"><span data-stu-id="47702-126">Partner Center user roles</span></span>|<span data-ttu-id="47702-127">Der Mitarbeiter, der die Connectors installieren und verwenden soll, muss ein Administrator sein.</span><span class="sxs-lookup"><span data-stu-id="47702-127">The employee who will install and use the connectors must be a Referrals admin</span></span>|[<span data-ttu-id="47702-128">Zuweisen von Rollen und Berechtigungen zu Benutzern</span><span class="sxs-lookup"><span data-stu-id="47702-128">Assign users roles and permissions</span></span>](create-user-accounts-and-set-permissions.md)|
|<span data-ttu-id="47702-129">Salesforce-CRM</span><span class="sxs-lookup"><span data-stu-id="47702-129">Salesforce CRM</span></span>|<span data-ttu-id="47702-130">Die CRM-Benutzerrolle ist Systemadministrator oder SystemCustomizer.</span><span class="sxs-lookup"><span data-stu-id="47702-130">The CRM user role is System admin or System customizer</span></span>|[<span data-ttu-id="47702-131">Zuweisen von Rollen in Dynamics 365</span><span class="sxs-lookup"><span data-stu-id="47702-131">Assign roles in Dynamics 365</span></span>](https://docs.microsoft.com/dynamics365/customerengagement/on-premises/customize/privileges-required-customization)|
|<span data-ttu-id="47702-132">Energie automatisierter Fluss Konto</span><span class="sxs-lookup"><span data-stu-id="47702-132">Power Automate Flow Account</span></span>|<span data-ttu-id="47702-133">Ein aktives, [Energie automatisierbares](https://flow.microsoft.com) Konto für den CRM-Systemadministrator oder den SystemCustomizer.</span><span class="sxs-lookup"><span data-stu-id="47702-133">An active [Power Automate](https://flow.microsoft.com) account for the CRM System admin or System customizer.</span></span> <span data-ttu-id="47702-134">Dieser Benutzer sollte sich mindestens einmal vor der Installation bei der [Strom Automatisierung](https://flow.microsoft.com) anmelden.</span><span class="sxs-lookup"><span data-stu-id="47702-134">That user should sign into [Power Automate](https://flow.microsoft.com) at least once before installation.</span></span>|

## <a name="install-partner-center-referrals-synchronization-for-salesforce-crm"></a><span data-ttu-id="47702-135">Installieren der Partner Center-Synchronisierung für Salesforce CRM</span><span class="sxs-lookup"><span data-stu-id="47702-135">Install Partner Center Referrals Synchronization for Salesforce CRM</span></span>

1. <span data-ttu-id="47702-136">Wechseln Sie zu " [Energie Automatisierung](https://flow.microsoft.com) ", und wählen Sie in der rechten oberen Ecke **Umgebungen** aus.</span><span class="sxs-lookup"><span data-stu-id="47702-136">Go to [Power Automate](https://flow.microsoft.com) and select **Environments** on the right top corner.</span></span> <span data-ttu-id="47702-137">Dadurch werden die verfügbaren CRM-Instanzen angezeigt.</span><span class="sxs-lookup"><span data-stu-id="47702-137">This will show you the available CRM instances.</span></span>

2. <span data-ttu-id="47702-138">Wählen Sie in der Dropdown-Dropdown-Ecke in der rechten oberen Ecke die entsprechende CRM-Instanz aus.</span><span class="sxs-lookup"><span data-stu-id="47702-138">Select the appropriate CRM instance from the drop-down on the right top corner.</span></span> 

3. <span data-ttu-id="47702-139">Wählen Sie in der linken Navigationsleiste **Lösungen** aus.</span><span class="sxs-lookup"><span data-stu-id="47702-139">Select **Solutions** on the left navigation bar.</span></span>

4. <span data-ttu-id="47702-140">Klicken Sie im oberen Menü auf den Link **appsource öffnen** .</span><span class="sxs-lookup"><span data-stu-id="47702-140">Click on the **Open AppSource** link on the top menu.</span></span>

![Appsource öffnen](images/cosellconnectors/openappsource.png)

5. <span data-ttu-id="47702-142">Suchen Sie im Popup-Bildschirm nach **Partner Center-verweisverweisconnectors für Salesforce** .</span><span class="sxs-lookup"><span data-stu-id="47702-142">Search for **Partner Center Referrals Connectors for Salesforce** in the pop-up screen.</span></span>  

6. <span data-ttu-id="47702-143">Klicken Sie auf die Schaltfläche **jetzt starten** und dann auf **weiter**.</span><span class="sxs-lookup"><span data-stu-id="47702-143">Click the **Get it now** button and then **Continue**.</span></span> 

7. <span data-ttu-id="47702-144">Dadurch wird die Seite geöffnet, auf der Sie die CRM-Umgebung (Dynamics 365) zum Installieren der Anwendung auswählen können.</span><span class="sxs-lookup"><span data-stu-id="47702-144">This opens the page where you can select the CRM (Dynamics 365) environment to install application.</span></span>  <span data-ttu-id="47702-145">Stimmen Sie den Geschäftsbedingungen zu.</span><span class="sxs-lookup"><span data-stu-id="47702-145">Agree to terms and conditions.</span></span> 

8. <span data-ttu-id="47702-146">Anschließend werden Sie zur Seite **Verwalten Ihrer Lösungen** weitergeleitet.</span><span class="sxs-lookup"><span data-stu-id="47702-146">You are then directed to the **Manage your solutions** page.</span></span>  <span data-ttu-id="47702-147">Navigieren Sie zu "Partner Center-Verweise", indem Sie die Pfeil Schaltflächen unten auf der Seite verwenden.</span><span class="sxs-lookup"><span data-stu-id="47702-147">Navigate to "Partner Center Referrals" by using the arrow buttons on the bottom of the page.</span></span> <span data-ttu-id="47702-148">Die **geplante Installation** sollte neben der Projekt Mappe für Partner Center-Verweise angezeigt werden.</span><span class="sxs-lookup"><span data-stu-id="47702-148">**Installation scheduled** should appear next to Partner Center Referrals solution.</span></span> <span data-ttu-id="47702-149">Die Installation wird 10-15 Minuten dauern.</span><span class="sxs-lookup"><span data-stu-id="47702-149">Installation will take 10-15 minutes.</span></span> 

9. <span data-ttu-id="47702-150">Nachdem die Installation fertiggestellt ist, navigieren Sie zurück zu [Energie Automatisierung](https://flow.microsoft.com) , und wählen Sie im linken Navigationsbereich **Lösungen** aus.</span><span class="sxs-lookup"><span data-stu-id="47702-150">Once the installation is complete, navigate back to [Power Automate](https://flow.microsoft.com) and select **Solutions** from left navigation area.</span></span> <span data-ttu-id="47702-151">Beachten Sie, dass die **Synchronisierung der Partner Center-Verweise für Salesforce** in der Lösungs Liste verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="47702-151">Notice that **Partner Center Referrals Synchronization for Salesforce** is available in the Solutions list.</span></span>

10. <span data-ttu-id="47702-152">Wählen Sie **Partner Center-Synchronisierungs Referenz für Dynamics 365 aus**.</span><span class="sxs-lookup"><span data-stu-id="47702-152">Select **Partner Center Referrals Synchronization for Dynamics 365**.</span></span> <span data-ttu-id="47702-153">Die folgenden Strom automatisierten Flows und Entitäten sind verfügbar:</span><span class="sxs-lookup"><span data-stu-id="47702-153">The following Power Automate flows and entities are available:</span></span>

![Verfügbare CRMs](images/cosellconnectors/dynamics-available-crms.png)

## <a name="best-practice-test-before-you-go-live"></a><span data-ttu-id="47702-155">Bewährte Vorgehensweise: testen, bevor Sie fortfahren</span><span class="sxs-lookup"><span data-stu-id="47702-155">Best Practice: Test before you go live</span></span>

<span data-ttu-id="47702-156">Stellen Sie sicher, dass Sie die Lösung in einer-Staging-Instanz von CRM testen, bevor Sie die Energie automatisierte Lösung in der Produktionsumgebung installieren, konfigurieren und anpassen.</span><span class="sxs-lookup"><span data-stu-id="47702-156">Before you install, configure, and customize the Power Automate solution on the production environment, be sure to test the solution on a staging CRM instance.</span></span>

- <span data-ttu-id="47702-157">Installieren Sie die Microsoft powerautomatisieren-Lösung auf einer Staging-Umgebung/CRM-Instanz.</span><span class="sxs-lookup"><span data-stu-id="47702-157">Install Microsoft Power Automate solution on a staging environment/CRM instance.</span></span>
- <span data-ttu-id="47702-158">Erstellen Sie eine Kopie der Projekt Mappe, und führen Sie Ihre Konfiguration aus, und automatisieren Sie Fluss Anpassungen in der Stagingumgebung.</span><span class="sxs-lookup"><span data-stu-id="47702-158">Make a copy of the solution and perform your configuration and Power Automate flow customizations on the staging environment.</span></span>
- <span data-ttu-id="47702-159">Testen Sie die Lösung auf einer Staging/CRM-Instanz.</span><span class="sxs-lookup"><span data-stu-id="47702-159">Test the solution on a staging/CRM instance.</span></span> 
- <span data-ttu-id="47702-160">Importieren Sie bei Erfolg als verwaltete Lösung in die Produktions Instanz.</span><span class="sxs-lookup"><span data-stu-id="47702-160">On success, import as managed solution to the production instance.</span></span> 

## <a name="configure-the-solution"></a><span data-ttu-id="47702-161">Konfigurieren der Projektmappe</span><span class="sxs-lookup"><span data-stu-id="47702-161">Configure the solution</span></span>

1. <span data-ttu-id="47702-162">Nachdem Sie die Lösung in Ihrer CRM-Instanz installiert haben, navigieren Sie zurück zu [Energie Automatisierung](https://flow.microsoft.com/).</span><span class="sxs-lookup"><span data-stu-id="47702-162">Once you have installed the solution in your CRM instance, navigate back to [Power Automate](https://flow.microsoft.com/).</span></span>

2. <span data-ttu-id="47702-163">Wählen Sie in der Dropdown- **Umgebung** in der rechten oberen Ecke die CRM-Instanz aus, auf der Sie die Energie automatisierte Lösung installiert haben.</span><span class="sxs-lookup"><span data-stu-id="47702-163">From the **Environments** drop-down on the right top corner, select the CRM instance where you installed the Power Automate solution.</span></span>

3. <span data-ttu-id="47702-164">Sie müssen Verbindungen erstellen, die die drei Benutzerkonten zuordnen:</span><span class="sxs-lookup"><span data-stu-id="47702-164">You will need to create connections that associate the three user accounts:</span></span> 

- <span data-ttu-id="47702-165">Partner Center-Benutzer mit referenrals Administrator Anmelde Informationen</span><span class="sxs-lookup"><span data-stu-id="47702-165">Partner Center user with referrals admin credentials</span></span> 
- <span data-ttu-id="47702-166">Partner Center-Ereignisse</span><span class="sxs-lookup"><span data-stu-id="47702-166">Partner Center Events</span></span>
- <span data-ttu-id="47702-167">Der CRM-Administrator mit den Energie automatisierten Flows in der Lösung.</span><span class="sxs-lookup"><span data-stu-id="47702-167">CRM admin with the Power Automate flows in the solution.</span></span> 

    <span data-ttu-id="47702-168">ein.</span><span class="sxs-lookup"><span data-stu-id="47702-168">a.</span></span> <span data-ttu-id="47702-169">Wählen Sie in der linken Navigationsleiste **Verbindungen** aus, und wählen Sie die Projekt Mappe "Partner Center-Verweise" aus der Liste aus.</span><span class="sxs-lookup"><span data-stu-id="47702-169">Select **Connections** from the left navigation bar and select the “Partner Center Referrals” solution from the list.</span></span>
    <span data-ttu-id="47702-170">b.</span><span class="sxs-lookup"><span data-stu-id="47702-170">b.</span></span> <span data-ttu-id="47702-171">Erstellen Sie eine Verbindung, indem Sie auf **Verbindung erstellen**klicken.</span><span class="sxs-lookup"><span data-stu-id="47702-171">Create a connection by clicking **Create a connection**.</span></span> 

    ![Erstellen der Verbindung](images/cosellconnectors/createconnection.png)

    <span data-ttu-id="47702-173">c.</span><span class="sxs-lookup"><span data-stu-id="47702-173">c.</span></span> <span data-ttu-id="47702-174">Suchen Sie in der Suchleiste in der oberen rechten Ecke nach **Partner Center-Referenzen (Vorschau)** .</span><span class="sxs-lookup"><span data-stu-id="47702-174">Search for **Partner Center Referrals (preview)** in the search bar on the top right corner.</span></span>
    <span data-ttu-id="47702-175">d.</span><span class="sxs-lookup"><span data-stu-id="47702-175">d.</span></span> <span data-ttu-id="47702-176">Erstellen Sie eine Verbindung für Ihren Partner Center-Benutzer mit der Rolle "Anmelde Informationen" des Administrators "Administrator". Fresser.</span><span class="sxs-lookup"><span data-stu-id="47702-176">Create a connection for your Partner Center user with the credentials role of Referrals admin. e.</span></span> <span data-ttu-id="47702-177">Erstellen Sie als nächstes eine Partner Center-Ereignis Verbindung für Ihren Partner Center-Benutzer mit den Anmelde Informationen für den Administrator. c.</span><span class="sxs-lookup"><span data-stu-id="47702-177">Next, create a Partner Center Events connection for your Partner Center user with the credentials of Referrals admin. f.</span></span> <span data-ttu-id="47702-178">Erstellen Sie eine Verbindung für Common Data Service (aktuelle Umgebung) für den CRM-Administrator Benutzer.</span><span class="sxs-lookup"><span data-stu-id="47702-178">Create a connection for Common Data Service (current environment) for the CRM administrator user.</span></span>

4. <span data-ttu-id="47702-179">Um die Strom automatisierten Flows den Verbindungen zuzuordnen, bearbeiten Sie jeden der Strom automatisierten Flows, um eine Verbindung mit Common Data Service-und Partner Center-Referenzen herzustellen.</span><span class="sxs-lookup"><span data-stu-id="47702-179">To associate the Power Automate flows with the connections, edit each of the Power Automate flows to connect to Common Data Service and Partner Center Referrals.</span></span> <span data-ttu-id="47702-180">Speichern Sie die Änderungen.</span><span class="sxs-lookup"><span data-stu-id="47702-180">Save the changes.</span></span>

5. <span data-ttu-id="47702-181">**Schalten** Sie die Strom automatisierten Flows ein.</span><span class="sxs-lookup"><span data-stu-id="47702-181">**Turn on** the the Power Automate flows.</span></span>

## <a name="next-steps"></a><span data-ttu-id="47702-182">Nächste Schritte</span><span class="sxs-lookup"><span data-stu-id="47702-182">Next steps</span></span>

- [<span data-ttu-id="47702-183">Verwenden von webhooks zum erhalten von Ressourcen Änderungs Ereignissen</span><span class="sxs-lookup"><span data-stu-id="47702-183">Use Webhooks to get resource change events</span></span>](referral-connector-webhooks.md)

- [<span data-ttu-id="47702-184">Weitere Informationen zur Microsoft powerautomatisieren-Plattform</span><span class="sxs-lookup"><span data-stu-id="47702-184">More about Microsoft Power Automate platform?</span></span>](https://docs.microsoft.com/power-automate/)

- [<span data-ttu-id="47702-185">Verwalten von Leads</span><span class="sxs-lookup"><span data-stu-id="47702-185">Manage leads</span></span>](manage-leads.md)

- [<span data-ttu-id="47702-186">Co-Selling-Verkaufschancen</span><span class="sxs-lookup"><span data-stu-id="47702-186">Manage co-sell opportunities</span></span>](manage-co-sell-opportunities.md)