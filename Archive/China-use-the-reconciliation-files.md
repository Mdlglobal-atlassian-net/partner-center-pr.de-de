---
title: Verwenden Sie die abstimmungsdateien (Partner Center im Betrieb über 21Vianet)
ms.topic: article
ms.date: 10/29/2018
description: Laden Sie die Abgleichungsdateien aus dem Partner Center-Dashboard herunter, um detaillierte Rechnungspositionsinformationen für einen Abrechnungszyklus anzuzeigen.
ms.assetid: FA6A6FCB-2597-44E7-93F8-8D1DD35D52EA
author: KPacquer
ms.author: kenpacq
ms.openlocfilehash: 30e3b7a7933678c4af079bb86aa1439559387f2b
ms.sourcegitcommit: 4c34d6fcaf020bcc53eaa5f0379011a56149a14f
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 03/05/2019
ms.locfileid: "57584983"
---
# <a name="use-the-reconciliation-files"></a><span data-ttu-id="23587-103">Verwenden der Abstimmungsdateien</span><span class="sxs-lookup"><span data-stu-id="23587-103">Use the reconciliation files</span></span>

<span data-ttu-id="23587-104">**Gilt für**</span><span class="sxs-lookup"><span data-stu-id="23587-104">**Applies to**</span></span>

-   <span data-ttu-id="23587-105">Partner Center-Betreiber ist 21Vianet</span><span class="sxs-lookup"><span data-stu-id="23587-105">Partner Center operated by 21Vianet</span></span>


<span data-ttu-id="23587-106">Laden Sie die Abgleichungsdateien aus dem Partner Center-Dashboard herunter, um detaillierte Rechnungspositionsinformationen für einen Abrechnungszyklus anzuzeigen.</span><span class="sxs-lookup"><span data-stu-id="23587-106">For a detailed line-item view of each charge in a billing cycle, download the reconciliation files from the Partner Center dashboard.</span></span> <span data-ttu-id="23587-107">Zu diesen Informationen zählen Gebühren für die einzelnen Abonnements von Kunden und ausführliche Ereignisinformationen (wie z. B. das Hinzufügen von Arbeitsplätzen zu einem Abonnement mitten in einem Abrechnungszeitraum).</span><span class="sxs-lookup"><span data-stu-id="23587-107">The details include charges for each customer's subscriptions, and detailed events (such as a mid-term addition of seats to a subscription).</span></span>

## <a href="" id="itemizebypartner"></a><span data-ttu-id="23587-108">Vom Partner aufschlüsseln</span><span class="sxs-lookup"><span data-stu-id="23587-108">Itemize by partner</span></span>


<span data-ttu-id="23587-109">Partner im indirekten Modell können diese zusätzlichen Felder in den beiden lizenzbasierten und nutzungsbasierten Abstimmungsdateien verwenden, um nach Handelspartnern aufzuschlüsseln.</span><span class="sxs-lookup"><span data-stu-id="23587-109">Partners in the indirect model can use these additional fields in both license-based and usage-based reconciliation files to itemize by reseller.</span></span>

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th><span data-ttu-id="23587-110">MPN-ID</span><span class="sxs-lookup"><span data-stu-id="23587-110">MPN ID</span></span></th>
<th><span data-ttu-id="23587-111">Beschreibung</span><span class="sxs-lookup"><span data-stu-id="23587-111">Description</span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="23587-112">MPN-ID</span><span class="sxs-lookup"><span data-stu-id="23587-112">MPN ID</span></span></td>
<td><p><span data-ttu-id="23587-113">Die Microsoft Partner Network (MPN)-ID des CSP-Partners (direkt oder indirekt).</span><span class="sxs-lookup"><span data-stu-id="23587-113">The Microsoft Partner Network (MPN) ID of the CSP partner (direct or indirect).</span></span></p></td>
</tr>
<tr class="even">
<td><span data-ttu-id="23587-114">MPN-ID der Handelspartner</span><span class="sxs-lookup"><span data-stu-id="23587-114">Reseller MPN ID</span></span></td>
<td><p><span data-ttu-id="23587-115">Wird nur in den Abstimmungsdateien für Partner im indirekten Modell angezeigt.</span><span class="sxs-lookup"><span data-stu-id="23587-115">Only appears on reconciliation files for partners in the indirect model.</span></span></p>
<p><span data-ttu-id="23587-116">Die MPN-ID des registrierten Handelspartners für das Abonnement.</span><span class="sxs-lookup"><span data-stu-id="23587-116">The MPN ID of the reseller of record for the subscription.</span></span> <span data-ttu-id="23587-117">Dies entspricht der Handelspartner-ID, die für das spezifische Abonnement im Partner Center aufgeführt ist.</span><span class="sxs-lookup"><span data-stu-id="23587-117">This corresponds to the reseller ID listed for the specific subscription in Partner Center.</span></span></p>
<p><span data-ttu-id="23587-118">Wählen Sie zum Anzeigen oder Aktualisieren des Handelspartners im Menü „Partner Center” <strong>Kunden</strong> aus, und wählen Sie dann den Kunden aus der Liste aus.</span><span class="sxs-lookup"><span data-stu-id="23587-118">eTo view or update the reseller, in the Partner Center menu, select <strong>Customers</strong>, then choose the customer from the list.</span></span> <span data-ttu-id="23587-119">Wählen Sie im Menü „Kunden” <strong>Abonnements</strong> und dann das Abonnement aus der Liste aus.</span><span class="sxs-lookup"><span data-stu-id="23587-119">In the customer menu, select <strong>Subscriptions</strong>, choose the subscription from the list.</span></span> <span data-ttu-id="23587-120">Wählen Sie <strong>Aktualisieren</strong> aus, um <strong>Vertriebspartner (MPN-ID)</strong> zu ändern.</span><span class="sxs-lookup"><span data-stu-id="23587-120">Select <strong>update</strong> to change the <strong>Reseller (MPN ID)</strong>.</span></span></p>
<p><span data-ttu-id="23587-121">Wenn ein CSP-Partner das Abonnement direkt an den Kunden veräußert hat, wird seine MPN-ID zweimal aufgeführt: als MPN-ID und als MPN-ID des Handelspartners.</span><span class="sxs-lookup"><span data-stu-id="23587-121">If a CSP partner sold the subscription directly to the customer, their MPN ID is listed twice, as both the MPN ID and the Reseller MPN ID.</span></span></p>
<p><span data-ttu-id="23587-122">Wenn ein CSP-Partner über einen Handelspartner ohne MPN-ID verfügt, wird dieser Wert stattdessen auf die MPN-ID des Partners festgelegt.</span><span class="sxs-lookup"><span data-stu-id="23587-122">If a CSP partner has a reseller with no MPN ID, this value is set to the partner’s MPN ID instead.</span></span></p>
<p><span data-ttu-id="23587-123">Wenn der CSP-Partner eine Handelspartner-ID entfernt, wird dieser Wert auf-1 festgelegt.</span><span class="sxs-lookup"><span data-stu-id="23587-123">If the CSP partner removes a reseller ID, this value will be set to -1.</span></span></p></td>
</tr>
</tbody>
</table>

 

## <a href="" id="licensebasedfiles"></a> <span data-ttu-id="23587-124">Lizenz-Datei-Felder</span><span class="sxs-lookup"><span data-stu-id="23587-124">License-based file fields</span></span>


<span data-ttu-id="23587-125">Um Ihre Gebühren mit den Bestellungen Ihrer Kunden abzugleichen, vergleichen Sie die Informationen unter Syndication\_Partner\_Subscription\_Number in der Abgleichungsdatei mit der Abonnement-ID aus Partner Center.</span><span class="sxs-lookup"><span data-stu-id="23587-125">To reconcile your charges against your customer's orders, compare the Syndication\_Partner\_Subscription\_Number from the reconciliation file against the Subscription ID from Partner Center.</span></span>

<table>
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span data-ttu-id="23587-126"><strong>Spalte</strong></span><span class="sxs-lookup"><span data-stu-id="23587-126"><strong>Column</strong></span></span></td>
<td><span data-ttu-id="23587-127"><strong>Beschreibung</strong></span><span class="sxs-lookup"><span data-stu-id="23587-127"><strong>Description</strong></span></span></td>
<td><span data-ttu-id="23587-128"><strong>Beispielwert</strong></span><span class="sxs-lookup"><span data-stu-id="23587-128"><strong>Sample Value</strong></span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="23587-129">PartnerID</span><span class="sxs-lookup"><span data-stu-id="23587-129">PartnerId</span></span></td>
<td><p><span data-ttu-id="23587-130">Eindeutiger Bezeichner für eine spezifische Abrechnungsentität im GUID-Format.</span><span class="sxs-lookup"><span data-stu-id="23587-130">Unique identifier for a specific billing entity, in GUID format.</span></span> <span data-ttu-id="23587-131">Nicht zur Abstimmung erforderlich, kann jedoch hilfreiche Informationen bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="23587-131">Not required for reconciliation, however may be useful information.</span></span> <span data-ttu-id="23587-132">In allen Zeilen gleich.</span><span class="sxs-lookup"><span data-stu-id="23587-132">Same in all rows.</span></span></p></td>
<td><span data-ttu-id="23587-133">8ddd03642-test-test-test-46b58d356b4e</span><span class="sxs-lookup"><span data-stu-id="23587-133">8ddd03642-test-test-test-46b58d356b4e</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="23587-134">CustomerID</span><span class="sxs-lookup"><span data-stu-id="23587-134">CustomerID</span></span></td>
<td><p><span data-ttu-id="23587-135">Eindeutige Microsoft-ID im GUID-Format: wird zur Identifizierung des Kunden verwendet.</span><span class="sxs-lookup"><span data-stu-id="23587-135">Unique Microsoft ID, in GUID format, used to identify the customer.</span></span></p></td>
<td><span data-ttu-id="23587-136">12ABCD34-001A-BCD2-987C-3210ABCD5678</span><span class="sxs-lookup"><span data-stu-id="23587-136">12ABCD34-001A-BCD2-987C-3210ABCD5678</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="23587-137">OrderID</span><span class="sxs-lookup"><span data-stu-id="23587-137">OrderID</span></span></td>
<td><p><span data-ttu-id="23587-138">Eindeutiger Bezeichner für eine Bestellung auf der Microsoft-Abrechnungsplattform.</span><span class="sxs-lookup"><span data-stu-id="23587-138">Unique identifier for an order in the Microsoft billing platform.</span></span> <span data-ttu-id="23587-139">Kann beim Kontakt zum Support zum Identifizieren der Bestellung hilfreich sein, jedoch nicht zur Abstimmung.</span><span class="sxs-lookup"><span data-stu-id="23587-139">May be useful to identify the order when contacting support but not for reconciliation.</span></span></p></td>
<td><span data-ttu-id="23587-140">566890604832738111</span><span class="sxs-lookup"><span data-stu-id="23587-140">566890604832738111</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="23587-141">SubscriptionID</span><span class="sxs-lookup"><span data-stu-id="23587-141">SubscriptionID</span></span></td>
<td><p><span data-ttu-id="23587-142">Eindeutiger Bezeichner für ein Abonnement auf der Microsoft-Abrechnungsplattform.</span><span class="sxs-lookup"><span data-stu-id="23587-142">Unique identifier for a subscription in the Microsoft billing platform.</span></span> <span data-ttu-id="23587-143">Kann zum Identifizieren des Abonnements bei einer Supportanfrage nützlich sein, dient jedoch nicht zu Abstimmungszwecken.</span><span class="sxs-lookup"><span data-stu-id="23587-143">May be useful to identify the subscription when contacting support but not for reconciliation.</span></span></p>
<p><span data-ttu-id="23587-144">Diese unterscheidet sich von der Abonnement-ID auf der Partner-Administratorkonsole.</span><span class="sxs-lookup"><span data-stu-id="23587-144">This is not the same as the Subscription ID on the Partner Admin Console.</span></span> <span data-ttu-id="23587-145">Siehe Syndication_Partner_Subscription_Number.</span><span class="sxs-lookup"><span data-stu-id="23587-145">Please see Syndication_Partner_Subscription_Number.</span></span></p></td>
<td><span data-ttu-id="23587-146">usCBMgAAAAAAAAIA</span><span class="sxs-lookup"><span data-stu-id="23587-146">usCBMgAAAAAAAAIA</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="23587-147">SyndicationPartnerSubscriptionNumber</span><span class="sxs-lookup"><span data-stu-id="23587-147">SyndicationPartnerSubscriptionNumber</span></span></td>
<td><p><span data-ttu-id="23587-148">Eindeutiger Bezeichner des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="23587-148">Unique identifier for subscriptions.</span></span> <span data-ttu-id="23587-149">Ein Kunde kann über mehrere Abonnements für denselben Plan verfügen, daher ist dies für die Analyse der Erstattungsdatei wichtig.</span><span class="sxs-lookup"><span data-stu-id="23587-149">A customer can have multiple subscriptions for the same plan, so this is important for reconciliation file analysis.</span></span></p>
<p><span data-ttu-id="23587-150">Dieses Feld ist der Abonnement-ID in der Partner-Administratorkonsole zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="23587-150">This field maps to the Subscription ID in the Partner Admin Console.</span></span></p></td>
<td><span data-ttu-id="23587-151">fb977ab5-test-test-test-24c8d9591708</span><span class="sxs-lookup"><span data-stu-id="23587-151">fb977ab5-test-test-test-24c8d9591708</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="23587-152">OfferID</span><span class="sxs-lookup"><span data-stu-id="23587-152">OfferID</span></span></td>
<td><p><span data-ttu-id="23587-153">Eindeutige Angebot-ID.</span><span class="sxs-lookup"><span data-stu-id="23587-153">Unique offer ID.</span></span> <span data-ttu-id="23587-154">Standard-Angebot-ID gemäß der Preisliste.</span><span class="sxs-lookup"><span data-stu-id="23587-154">Standard offer ID as per price list.</span></span></p>
<p><span data-ttu-id="23587-155"><b>Hinweis</b>: Dieser Wert entspricht nicht den Angebots-ID aus der Preisliste.</span><span class="sxs-lookup"><span data-stu-id="23587-155"><b>Note</b>: This value does not match Offer ID from the price list.</span></span> <span data-ttu-id="23587-156">Siehe DurableOfferID unten.</span><span class="sxs-lookup"><span data-stu-id="23587-156">See DurableOfferID below.</span></span></p></td>
<td><span data-ttu-id="23587-157">FE616D64-E9A8-40EF-843F-152E9BBEF3D1</span><span class="sxs-lookup"><span data-stu-id="23587-157">FE616D64-E9A8-40EF-843F-152E9BBEF3D1</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="23587-158">DurableOfferID</span><span class="sxs-lookup"><span data-stu-id="23587-158">DurableOfferID</span></span></td>
<td><p><span data-ttu-id="23587-159">Eindeutige dauerhafte Angebot-ID gemäß Definition in der Preisliste.</span><span class="sxs-lookup"><span data-stu-id="23587-159">Unique durable offer ID, as defined in the price list.</span></span></p>
<p><span data-ttu-id="23587-160"><b>Hinweis</b>: Dieser Wert entspricht der Angebots-ID aus der Preisliste.</span><span class="sxs-lookup"><span data-stu-id="23587-160"><b>Note</b>: This value matches the Offer ID from the price list.</span></span></p></td>
<td><span data-ttu-id="23587-161">1017D7F3-6D7F-4BFA-BDD8-79BC8F104E0C</span><span class="sxs-lookup"><span data-stu-id="23587-161">1017D7F3-6D7F-4BFA-BDD8-79BC8F104E0C</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="23587-162">OfferName</span><span class="sxs-lookup"><span data-stu-id="23587-162">OfferName</span></span></td>
<td><p><span data-ttu-id="23587-163">Der Name des Service-Angebots, das der Kunde gekauft hat, wie in der Preisliste definiert.</span><span class="sxs-lookup"><span data-stu-id="23587-163">The name of the service offering purchased by the customer, as defined in the price list.</span></span></p></td>
<td><span data-ttu-id="23587-164">Microsoft Office 365 (Plan E3)</span><span class="sxs-lookup"><span data-stu-id="23587-164">Microsoft Office 365 (Plan E3)</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="23587-165">SubscriptionStartDate</span><span class="sxs-lookup"><span data-stu-id="23587-165">SubscriptionStartDate</span></span></td>
<td><p><span data-ttu-id="23587-166">Das Anfangsdatum des Abonnements, festgelegt auf den Tag nach Übermittlung der Bestellung.</span><span class="sxs-lookup"><span data-stu-id="23587-166">The subscription start date, set to the day after the order is submitted.</span></span> <span data-ttu-id="23587-167">Wenn Sie das Anfangsdatum des Abonnements mit dem Enddatum vergleichen, können Sie feststellen, ob der Kunde sich noch im ersten Jahr des Abonnements befindet, oder ob das Abonnement für das folgende Jahr verlängert wurde.</span><span class="sxs-lookup"><span data-stu-id="23587-167">By looking at the subscription start date in conjunction with the end date, you can determine if the customer is still within the first year of the subscription or if the subscription has been renewed for the following year.</span></span></p>
<p><span data-ttu-id="23587-168">Die Uhrzeit ist immer auf den Tagesbeginn um 0:00 Uhr festgelegt.</span><span class="sxs-lookup"><span data-stu-id="23587-168">The time is always the beginning of the day, 0:00.</span></span></p></td>
<td><span data-ttu-id="23587-169">01.02.2015 0:00</span><span class="sxs-lookup"><span data-stu-id="23587-169">2/1/2015 0:00</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="23587-170">SubscriptionEndDate</span><span class="sxs-lookup"><span data-stu-id="23587-170">SubscriptionEndDate</span></span></td>
<td><p><span data-ttu-id="23587-171">Die Abonnement-Enddatum: 12 Monate + X Tage nach dem Startdatum (Partner Abrechnungsdatum in Anpassung an) oder 12 Monate ab Verlängerungsdatum.</span><span class="sxs-lookup"><span data-stu-id="23587-171">The subscription end date: 12 months + x days after start date (to align with partner billing date) or 12 months from renewal date.</span></span></p>
<p><span data-ttu-id="23587-172">Bei Verlängerung werden die Preise gemäß der aktuellen Preisliste aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="23587-172">At renewal, prices are updated to the current price list.</span></span> <span data-ttu-id="23587-173">Vor einer automatischen Verlängerung ist möglicherweise die Kommunikation mit dem Kunden erforderlich.</span><span class="sxs-lookup"><span data-stu-id="23587-173">Customer communication may be required in advance of automated renewal.</span></span></p>
<p><span data-ttu-id="23587-174">Die Uhrzeit ist immer auf den Tagesbeginn um 0:00 Uhr festgelegt.</span><span class="sxs-lookup"><span data-stu-id="23587-174">The time is always the beginning of the day, 0:00.</span></span></p></td>
<td><span data-ttu-id="23587-175">01.02.2015 0:00</span><span class="sxs-lookup"><span data-stu-id="23587-175">2/1/2015 0:00</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="23587-176">ChargeStartDate</span><span class="sxs-lookup"><span data-stu-id="23587-176">ChargeStartDate</span></span></td>
<td><p><span data-ttu-id="23587-177">Der erste Tag, an dem Gebühren anfallen.</span><span class="sxs-lookup"><span data-stu-id="23587-177">Start day of the charges.</span></span></p>
<p><span data-ttu-id="23587-178">Wenn ein Kunde die Anzahl der Arbeitsplätze ändert, werden anhand dieser Anzahl die Kosten pro Tag (anteilsmäßig) berechnet.</span><span class="sxs-lookup"><span data-stu-id="23587-178">When a customer changes seat numbers, this number is used to calculate per-day (pro-rata) charges.</span></span></p>
<p><span data-ttu-id="23587-179">Die Uhrzeit ist immer auf den Tagesbeginn um 0:00 Uhr festgelegt.</span><span class="sxs-lookup"><span data-stu-id="23587-179">The time is always the beginning of the day, 0:00.</span></span></p></td>
<td><span data-ttu-id="23587-180">01.02.2015 0:00</span><span class="sxs-lookup"><span data-stu-id="23587-180">2/1/2015 0:00</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="23587-181">ChargeEndDate</span><span class="sxs-lookup"><span data-stu-id="23587-181">ChargeEndDate</span></span></td>
<td><p><span data-ttu-id="23587-182">Letzter Tag, an dem Gebühren anfallen.</span><span class="sxs-lookup"><span data-stu-id="23587-182">End day of the charges.</span></span></p>
<p><span data-ttu-id="23587-183">Wenn ein Kunde die Anzahl der Arbeitsplätze ändert, werden anhand dieser Anzahl die Kosten pro Tag (anteilsmäßig) berechnet.</span><span class="sxs-lookup"><span data-stu-id="23587-183">When a customer changes seat numbers, this number is used to calculate per-day (pro-rata) charges.</span></span></p>
<p><span data-ttu-id="23587-184">Die Uhrzeit ist immer auf das Tagesende um 23:59 Uhr festgelegt.</span><span class="sxs-lookup"><span data-stu-id="23587-184">The time is always the end of the day, 23:59.</span></span></p></td>
<td><span data-ttu-id="23587-185">28.2.2015 23:59</span><span class="sxs-lookup"><span data-stu-id="23587-185">2/28/2015 23:59</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="23587-186">ChargeType</span><span class="sxs-lookup"><span data-stu-id="23587-186">ChargeType</span></span></td>
<td><p><span data-ttu-id="23587-187">Art der Gebühren oder der Anpassungen.</span><span class="sxs-lookup"><span data-stu-id="23587-187">The type of charge or adjustment.</span></span> <span data-ttu-id="23587-188">Siehe <a href="#charge_types">Zuordnung von Gebühren zwischen einer Rechnung und der Erstattungsdatei</a></span><span class="sxs-lookup"><span data-stu-id="23587-188">See <a href="#charge_types">Mapping charges between an invoice and the reconciliation file</a></span></span></p></td>
<td><p><span data-ttu-id="23587-189">Siehe <a href="#charge_types">Zuordnung von Gebühren zwischen einer Rechnung und der Erstattungsdatei</a></span><span class="sxs-lookup"><span data-stu-id="23587-189">See <a href="#charge_types">Mapping charges between an invoice and the reconciliation file</a></span></span></p></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="23587-190">UnitPrice</span><span class="sxs-lookup"><span data-stu-id="23587-190">UnitPrice</span></span></td>
<td><p><span data-ttu-id="23587-191">Preis pro Lizenz.</span><span class="sxs-lookup"><span data-stu-id="23587-191">Price per seat.</span></span> <span data-ttu-id="23587-192">Stellen Sie sicher, dass dies den Informationen entspricht, die in Ihrem Abrechnungssystem während der Abstimmung gespeichert wurden.</span><span class="sxs-lookup"><span data-stu-id="23587-192">Ensure this matches the information stored in your billing system during reconciliation.</span></span></p></td>
<td><span data-ttu-id="23587-193">6,82</span><span class="sxs-lookup"><span data-stu-id="23587-193">6.82</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="23587-194">Anzahl</span><span class="sxs-lookup"><span data-stu-id="23587-194">Quantity</span></span></td>
<td><p><span data-ttu-id="23587-195">Anzahl der Arbeitsplätze</span><span class="sxs-lookup"><span data-stu-id="23587-195">Number of seats.</span></span> <span data-ttu-id="23587-196">Stellen Sie sicher, dass dies den Informationen entspricht, die in Ihrem Abrechnungssystem während der Abstimmung gespeichert wurden.</span><span class="sxs-lookup"><span data-stu-id="23587-196">Ensure this matches the information stored in your billing system during reconciliation.</span></span></p></td>
<td><span data-ttu-id="23587-197">2</span><span class="sxs-lookup"><span data-stu-id="23587-197">2</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="23587-198">Betrag</span><span class="sxs-lookup"><span data-stu-id="23587-198">Amount</span></span></td>
<td><p><span data-ttu-id="23587-199">Gesamtpreis für die Menge</span><span class="sxs-lookup"><span data-stu-id="23587-199">Total of price for quantity.</span></span> <span data-ttu-id="23587-200">Hilfreich der Überprüfung, dass die Betragsberechnung mit der Abrechnung für Ihre Kunden übereinstimmt.</span><span class="sxs-lookup"><span data-stu-id="23587-200">Useful to check that the amount calculation matches how you calculate this for your customers.</span></span></p></td>
<td><span data-ttu-id="23587-201">13,32</span><span class="sxs-lookup"><span data-stu-id="23587-201">13.32</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="23587-202">TotalOtherDiscount</span><span class="sxs-lookup"><span data-stu-id="23587-202">TotalOtherDiscount</span></span></td>
<td><p><span data-ttu-id="23587-203">Rabattbetrag auf diese Gebühren.</span><span class="sxs-lookup"><span data-stu-id="23587-203">Amount of discount applied to these charges.</span></span> <span data-ttu-id="23587-204">IUR (Internal Use Rights) oder neue Abonnements, die Anspruch auf einen Bonus haben, enthalten ebenfalls einen Rabattbetrag in dieser Spalte.</span><span class="sxs-lookup"><span data-stu-id="23587-204">IUR or new subscriptions eligible for an incentive will also contain a discount amount in this column.</span></span></p></td>
<td><span data-ttu-id="23587-205">2,32</span><span class="sxs-lookup"><span data-stu-id="23587-205">2.32</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="23587-206">Zwischensumme</span><span class="sxs-lookup"><span data-stu-id="23587-206">Subtotal</span></span></td>
<td><p><span data-ttu-id="23587-207">Gesamtbetrag vor Steuern</span><span class="sxs-lookup"><span data-stu-id="23587-207">Total before tax.</span></span> <span data-ttu-id="23587-208">Überprüft, ob bei Rabatten Ihre Zwischensumme mit dem erwarteten Gesamtbetrag übereinstimmt.</span><span class="sxs-lookup"><span data-stu-id="23587-208">Checks that your subtotal matches your expected total, in case of a discount.</span></span></p></td>
<td><span data-ttu-id="23587-209">11</span><span class="sxs-lookup"><span data-stu-id="23587-209">11</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="23587-210">Steuern</span><span class="sxs-lookup"><span data-stu-id="23587-210">Tax</span></span></td>
<td><p><span data-ttu-id="23587-211">USt.-Betrag auf der Grundlage der Steuervorschriften und spezifischen Gegebenheiten Ihres Markts.</span><span class="sxs-lookup"><span data-stu-id="23587-211">Tax amount charge, based on your market's tax rules and specific circumstances.</span></span></p></td>
<td><span data-ttu-id="23587-212">0</span><span class="sxs-lookup"><span data-stu-id="23587-212">0</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="23587-213">TotalForCustomer</span><span class="sxs-lookup"><span data-stu-id="23587-213">TotalForCustomer</span></span></td>
<td><p><span data-ttu-id="23587-214">Gesamtsumme nach Steuern.</span><span class="sxs-lookup"><span data-stu-id="23587-214">Total after tax.</span></span> <span data-ttu-id="23587-215">Überprüft, ob in der Rechnung Steuern berechnet werden.</span><span class="sxs-lookup"><span data-stu-id="23587-215">Checks if you are charged tax in the invoice.</span></span></p></td>
<td><span data-ttu-id="23587-216">11</span><span class="sxs-lookup"><span data-stu-id="23587-216">11</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="23587-217">Währung</span><span class="sxs-lookup"><span data-stu-id="23587-217">Currency</span></span></td>
<td><p><span data-ttu-id="23587-218">Währungstyp</span><span class="sxs-lookup"><span data-stu-id="23587-218">Currency type.</span></span> <span data-ttu-id="23587-219">Jede Abrechnungsentität verfügt nur über eine Währung.</span><span class="sxs-lookup"><span data-stu-id="23587-219">Each billing entity has only one currency.</span></span> <span data-ttu-id="23587-220">Überprüft auf Übereinstimmung in Ihrer ersten Rechnung und nach jedem großen Update der Abrechnungsplattform.</span><span class="sxs-lookup"><span data-stu-id="23587-220">Check that it matches your first invoice and then after any major billing platform update.</span></span></p></td>
<td><span data-ttu-id="23587-221">CNY</span><span class="sxs-lookup"><span data-stu-id="23587-221">CNY</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="23587-222">CustomerName</span><span class="sxs-lookup"><span data-stu-id="23587-222">CustomerName</span></span></td>
<td><p><span data-ttu-id="23587-223">Firmenname des Kunden wie im Partner Center angegeben.</span><span class="sxs-lookup"><span data-stu-id="23587-223">Customer's organization name as reported in Partner Center.</span></span> <span data-ttu-id="23587-224">Dies ist sehr wichtig für die Abstimmung der Rechnung mit Ihren Systeminformationen.</span><span class="sxs-lookup"><span data-stu-id="23587-224">This is very important for reconciling the invoice with your system information.</span></span></p></td>
<td><span data-ttu-id="23587-225">Test für Kunde A</span><span class="sxs-lookup"><span data-stu-id="23587-225">Test Customer A</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="23587-226">MPNID</span><span class="sxs-lookup"><span data-stu-id="23587-226">MPNID</span></span></td>
<td><p><span data-ttu-id="23587-227">MPN-ID des CSP-Partners</span><span class="sxs-lookup"><span data-stu-id="23587-227">MPN ID of the CSP partner</span></span></p></td>
<td><span data-ttu-id="23587-228">4390934</span><span class="sxs-lookup"><span data-stu-id="23587-228">4390934</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="23587-229">ResellerMPNID</span><span class="sxs-lookup"><span data-stu-id="23587-229">ResellerMPNID</span></span></td>
<td><p><span data-ttu-id="23587-230">MPN-ID des registrierten Handelspartners für das Abonnement.</span><span class="sxs-lookup"><span data-stu-id="23587-230">MPN ID of the reseller of record for the subscription.</span></span> <span data-ttu-id="23587-231">Siehe [Aufschlüsseln nach Partner](#itemizebypartner).</span><span class="sxs-lookup"><span data-stu-id="23587-231">See [Itemize by partner](#itemizebypartner).</span></span></p></td>
<td><span data-ttu-id="23587-232">4390934</span><span class="sxs-lookup"><span data-stu-id="23587-232">4390934</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="23587-233">DomainName</span><span class="sxs-lookup"><span data-stu-id="23587-233">DomainName</span></span></td>
<td><p><span data-ttu-id="23587-234">Kundendomänenname: wird zur Identifizierung des Kunden verwendet.</span><span class="sxs-lookup"><span data-stu-id="23587-234">Customer's domain name, used to help identify the customer.</span></span></p></td>
<td><span data-ttu-id="23587-235">example.onmicrosoft.com</span><span class="sxs-lookup"><span data-stu-id="23587-235">example.onmicrosoft.com</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="23587-236">SubscriptionName</span><span class="sxs-lookup"><span data-stu-id="23587-236">SubscriptionName</span></span></td>
<td><p><span data-ttu-id="23587-237">Abonnement-Nickname.</span><span class="sxs-lookup"><span data-stu-id="23587-237">Subscription nickname.</span></span> <span data-ttu-id="23587-238">Wenn kein Nickname angegeben ist, verwendet Partner Center den OfferName.</span><span class="sxs-lookup"><span data-stu-id="23587-238">If no nickname is specified, Partner Center uses the OfferName.</span></span></p></td>
<td><span data-ttu-id="23587-239">PROJECT ONLINE</span><span class="sxs-lookup"><span data-stu-id="23587-239">PROJECT ONLINE</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="23587-240">SubscriptionDescription</span><span class="sxs-lookup"><span data-stu-id="23587-240">SubscriptionDescription</span></span></td>
<td><p><span data-ttu-id="23587-241">Der Name des Service-Angebots, das der Kunde gekauft hat, wie in der Preisliste definiert.</span><span class="sxs-lookup"><span data-stu-id="23587-241">The name of the service offering purchased by the customer, as defined in the price list.</span></span> <span data-ttu-id="23587-242">(Dies ist ein identisches Feld für den Angebotsnamen).</span><span class="sxs-lookup"><span data-stu-id="23587-242">(This is an identical field to Offer name).</span></span></p></td>
<td><span data-ttu-id="23587-243">PROJECT ONLINE PREMIUM OHNE PROJECT-CLIENT</span><span class="sxs-lookup"><span data-stu-id="23587-243">PROJECT ONLINE PREMIUM WITHOUT PROJECT CLIENT</span></span></td>
</tr>
</tbody>
</table>


## <a href="" id="usagebasedfiles"></a><span data-ttu-id="23587-244">Nutzungsbasierte Dateifelder</span><span class="sxs-lookup"><span data-stu-id="23587-244">Usage-based file fields</span></span>


<span data-ttu-id="23587-245">Um Ihre Gebühren mit der Nutzung des Kunden abzugleichen, vergleichen Sie ResellerID/ResellerName/ResellerBillableAccount aus der Abgleichungsdatei, den Kundennamen und die Abonnement-ID in Partner Center.</span><span class="sxs-lookup"><span data-stu-id="23587-245">To reconcile your charges against your customer's usage, compare the ResellerID/ResellerName/ResellerBillableAccount from the reconciliation file, the customer name, and the Subscription ID from Partner Center.</span></span>

<span data-ttu-id="23587-246">Die folgenden Felder enthalten Informationen zu den verwendeten Diensten und den Raten.</span><span class="sxs-lookup"><span data-stu-id="23587-246">The following fields explain which services were used and the rate.</span></span>

<table>
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span data-ttu-id="23587-247"><strong>Spalte</strong></span><span class="sxs-lookup"><span data-stu-id="23587-247"><strong>Column</strong></span></span></td>
<td><span data-ttu-id="23587-248"><strong>Beschreibung</strong></span><span class="sxs-lookup"><span data-stu-id="23587-248"><strong>Description</strong></span></span></td>
<td><span data-ttu-id="23587-249"><strong>Beispielwert</strong></span><span class="sxs-lookup"><span data-stu-id="23587-249"><strong>Sample value</strong></span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="23587-250">PartnerID</span><span class="sxs-lookup"><span data-stu-id="23587-250">PartnerID</span></span></td>
<td><p><span data-ttu-id="23587-251">Partner-ID im GUID-Format.</span><span class="sxs-lookup"><span data-stu-id="23587-251">Partner ID, in GUID format.</span></span></p></td>
<td><span data-ttu-id="23587-252">DA41BC5F-C52D-4464-8A8D-8C8DCC43503B</span><span class="sxs-lookup"><span data-stu-id="23587-252">DA41BC5F-C52D-4464-8A8D-8C8DCC43503B</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="23587-253">PartnerName</span><span class="sxs-lookup"><span data-stu-id="23587-253">PartnerName</span></span></td>
<td><p><span data-ttu-id="23587-254">Partnername.</span><span class="sxs-lookup"><span data-stu-id="23587-254">Partner Name.</span></span></p></td>
<td><span data-ttu-id="23587-255">Acme integriert</span><span class="sxs-lookup"><span data-stu-id="23587-255">Acme Incorporated</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="23587-256">PartnerBillableAccountID</span><span class="sxs-lookup"><span data-stu-id="23587-256">PartnerBillableAccountID</span></span></td>
<td><p><span data-ttu-id="23587-257">Partner-Konto-ID.</span><span class="sxs-lookup"><span data-stu-id="23587-257">Partner Account ID.</span></span></p></td>
<td><span data-ttu-id="23587-258">1010578050</span><span class="sxs-lookup"><span data-stu-id="23587-258">1010578050</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="23587-259">CustomerName</span><span class="sxs-lookup"><span data-stu-id="23587-259">CustomerName</span></span></td>
<td><p><span data-ttu-id="23587-260">Firmenname des Kunden wie im Partner Center angegeben.</span><span class="sxs-lookup"><span data-stu-id="23587-260">Customer's organization name as reported in Partner Center.</span></span> <span data-ttu-id="23587-261">Dies ist sehr wichtig für die Abstimmung der Rechnung mit Ihren Systeminformationen.</span><span class="sxs-lookup"><span data-stu-id="23587-261">This is very important for reconciling the invoice with your system information.</span></span></p></td>
<td><span data-ttu-id="23587-262">Test für Kunde A</span><span class="sxs-lookup"><span data-stu-id="23587-262">Test Customer A</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="23587-263">MPNID</span><span class="sxs-lookup"><span data-stu-id="23587-263">MPNID</span></span></td>
<td><p><span data-ttu-id="23587-264">MPN-ID des CSP-Partners.</span><span class="sxs-lookup"><span data-stu-id="23587-264">MPN ID of the CSP partner.</span></span></p></td>
<td><span data-ttu-id="23587-265">4390934</span><span class="sxs-lookup"><span data-stu-id="23587-265">4390934</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="23587-266">ResellerMPNID</span><span class="sxs-lookup"><span data-stu-id="23587-266">ResellerMPNID</span></span></td>
<td><p><span data-ttu-id="23587-267">MPN-ID des registrierten Handelspartners für das Abonnement.</span><span class="sxs-lookup"><span data-stu-id="23587-267">MPN ID of the reseller of record for the subscription.</span></span> <span data-ttu-id="23587-268">Siehe [Aufschlüsseln nach Partner](#itemizebypartner).</span><span class="sxs-lookup"><span data-stu-id="23587-268">See [Itemize by partner](#itemizebypartner).</span></span></p></td>
<td><span data-ttu-id="23587-269">4390934</span><span class="sxs-lookup"><span data-stu-id="23587-269">4390934</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="23587-270">InvoiceNumber</span><span class="sxs-lookup"><span data-stu-id="23587-270">InvoiceNumber</span></span></td>
<td><p><span data-ttu-id="23587-271">Rechnungsnummer, in der die angegebene Transaktion angezeigt wird.</span><span class="sxs-lookup"><span data-stu-id="23587-271">Invoice number where the specified transaction appears.</span></span></p></td>
<td><span data-ttu-id="23587-272">D020001IVK</span><span class="sxs-lookup"><span data-stu-id="23587-272">D020001IVK</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="23587-273">ChargeStartDate</span><span class="sxs-lookup"><span data-stu-id="23587-273">ChargeStartDate</span></span></td>
<td><p><span data-ttu-id="23587-274">Anfangsdatum des Abrechnungszeitraums, außer wenn Datumsangaben zu zuvor nicht berechneten latenten Nutzungsdaten (aus dem vorherigen Abrechnungszyklus) vorliegen.</span><span class="sxs-lookup"><span data-stu-id="23587-274">Start date of billing cycle except when presenting dates of previously uncharged latent usage data (from previous bill cycle).</span></span></p>
<p><span data-ttu-id="23587-275">Die Uhrzeit ist immer auf den Tagesbeginn um 0:00 Uhr festgelegt.</span><span class="sxs-lookup"><span data-stu-id="23587-275">The time is always the beginning of the day, 0:00.</span></span></p></td>
<td><span data-ttu-id="23587-276">01.02.2014 0:00</span><span class="sxs-lookup"><span data-stu-id="23587-276">2/1/2014 0:00</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="23587-277">ChargeEndDate</span><span class="sxs-lookup"><span data-stu-id="23587-277">ChargeEndDate</span></span></td>
<td><p><span data-ttu-id="23587-278">Enddatum des Abrechnungszeitraums, außer wenn Datumsangaben zu zuvor nicht berechneten latenten Nutzungsdaten (aus dem vorherigen Abrechnungszyklus) vorliegen.</span><span class="sxs-lookup"><span data-stu-id="23587-278">End date of billing cycle except when presenting dates of previously uncharged latent usage data (from previous bill cycle).</span></span></p>
<p><span data-ttu-id="23587-279">Die Uhrzeit ist immer auf das Tagesende um 23:59 Uhr festgelegt.</span><span class="sxs-lookup"><span data-stu-id="23587-279">The time is always the end of the day, 23:59.</span></span></p></td>
<td><span data-ttu-id="23587-280">28.02.2014 23:59</span><span class="sxs-lookup"><span data-stu-id="23587-280">2/28/2014 23:59</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="23587-281">SubscriptionID</span><span class="sxs-lookup"><span data-stu-id="23587-281">SubscriptionID</span></span></td>
<td><p><span data-ttu-id="23587-282">Eindeutiger Bezeichner für ein Abonnement auf der Microsoft-Abrechnungsplattform.</span><span class="sxs-lookup"><span data-stu-id="23587-282">Unique identifier for a subscription in the Microsoft billing platform.</span></span> <span data-ttu-id="23587-283">Kann zum Identifizieren des Abonnements bei einer Supportanfrage nützlich sein, dient jedoch nicht zu Abstimmungszwecken.</span><span class="sxs-lookup"><span data-stu-id="23587-283">May be useful to identify the subscription when contacting support but not for reconciliation.</span></span></p>
<p><span data-ttu-id="23587-284">Diese unterscheidet sich von der Abonnement-ID auf der Partner-Administratorkonsole.</span><span class="sxs-lookup"><span data-stu-id="23587-284">This is not the same as the Subscription ID on the Partner Admin Console.</span></span></p></td>
<td><span data-ttu-id="23587-285">usCBMgAAAAAAAAIA</span><span class="sxs-lookup"><span data-stu-id="23587-285">usCBMgAAAAAAAAIA</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="23587-286">SubscriptionName</span><span class="sxs-lookup"><span data-stu-id="23587-286">SubscriptionName</span></span></td>
<td><p><span data-ttu-id="23587-287">Nickname des Service-Angebots.</span><span class="sxs-lookup"><span data-stu-id="23587-287">Nickname of the service offering.</span></span></p></td>
<td><span data-ttu-id="23587-288">Microsoft Azure</span><span class="sxs-lookup"><span data-stu-id="23587-288">Microsoft Azure</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="23587-289">SubscriptionDescription</span><span class="sxs-lookup"><span data-stu-id="23587-289">SubscriptionDescription</span></span></td>
<td><p><span data-ttu-id="23587-290">Branche des Service-Angebots</span><span class="sxs-lookup"><span data-stu-id="23587-290">Line of business of the service offering</span></span></p></td>
<td><span data-ttu-id="23587-291">Microsoft Azure</span><span class="sxs-lookup"><span data-stu-id="23587-291">Microsoft Azure</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="23587-292">OrderID</span><span class="sxs-lookup"><span data-stu-id="23587-292">OrderID</span></span></td>
<td><p><span data-ttu-id="23587-293">Eindeutiger Bezeichner für eine Bestellung auf der Microsoft-Abrechnungsplattform.</span><span class="sxs-lookup"><span data-stu-id="23587-293">Unique identifier for an order in the Microsoft billing platform.</span></span> <span data-ttu-id="23587-294">Kann zum Identifizieren des Abonnements bei einer Supportanfrage nützlich sein, dient jedoch nicht zu Abstimmungszwecken.</span><span class="sxs-lookup"><span data-stu-id="23587-294">May be useful to identify the subscription when contacting support but not for reconciliation.</span></span></p></td>
<td><span data-ttu-id="23587-295">566890604832738111</span><span class="sxs-lookup"><span data-stu-id="23587-295">566890604832738111</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="23587-296">ServiceName</span><span class="sxs-lookup"><span data-stu-id="23587-296">ServiceName</span></span></td>
<td><p><span data-ttu-id="23587-297">Der Name des fraglichen Azure-Dienstes</span><span class="sxs-lookup"><span data-stu-id="23587-297">The name of the Azure service in question.</span></span></p></td>
<td><span data-ttu-id="23587-298">VIRTUELLE COMPUTER</span><span class="sxs-lookup"><span data-stu-id="23587-298">VIRTUAL MACHINES</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="23587-299">ServiceType</span><span class="sxs-lookup"><span data-stu-id="23587-299">ServiceType</span></span></td>
<td><p><span data-ttu-id="23587-300">Der bestimmte Typ des Windows Azure-Dienstes.</span><span class="sxs-lookup"><span data-stu-id="23587-300">The specific type of Windows Azure service.</span></span></p></td>
<td><ul>
<li><span data-ttu-id="23587-301">Service Bus – einzeln oder als Paket</span><span class="sxs-lookup"><span data-stu-id="23587-301">Service Bus – Individual or Pack</span></span></li>
<li><span data-ttu-id="23587-302">SQL Azure-Datenbank – Business oder Web Edition</span><span class="sxs-lookup"><span data-stu-id="23587-302">SQL Azure database – Business or Web Edition</span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="23587-303">ResourceGUID</span><span class="sxs-lookup"><span data-stu-id="23587-303">ResourceGUID</span></span></td>
<td><p><span data-ttu-id="23587-304">Bestimmter eindeutiger Bezeichner für alle Dienstdaten und die Preisstruktur.</span><span class="sxs-lookup"><span data-stu-id="23587-304">Specific unique identifier for all the service data and pricing structure.</span></span></p></td>
<td><span data-ttu-id="23587-305">DA41BC5F-C52D-4464-8A8D-8C8DCC43503B</span><span class="sxs-lookup"><span data-stu-id="23587-305">DA41BC5F-C52D-4464-8A8D-8C8DCC43503B</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="23587-306">Ressourcenname</span><span class="sxs-lookup"><span data-stu-id="23587-306">Resource Name</span></span></td>
<td><p><span data-ttu-id="23587-307">Der Name der Azure-Ressource.</span><span class="sxs-lookup"><span data-stu-id="23587-307">The name of the Azure resource.</span></span></p></td>
<td><ul>
<li><span data-ttu-id="23587-308">Übertragung eingehender Daten (GB)</span><span class="sxs-lookup"><span data-stu-id="23587-308">Data Transfer In (GB)</span></span></li>
<li><span data-ttu-id="23587-309">Übertragung ausgehender Daten (GB)</span><span class="sxs-lookup"><span data-stu-id="23587-309">Data Transfer Out (GB)</span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="23587-310">Region</span><span class="sxs-lookup"><span data-stu-id="23587-310">Region</span></span></td>
<td><p><span data-ttu-id="23587-311">Die Region, auf die sich die Nutzung bezieht.</span><span class="sxs-lookup"><span data-stu-id="23587-311">The region the usage applies to.</span></span> <span data-ttu-id="23587-312">Wird in erster Linie zum Zuweisen von Tarifen für die Datenübertragung verwendet, da sich die Tarife je nach Region unterscheiden.</span><span class="sxs-lookup"><span data-stu-id="23587-312">Primarily used to assign rates to data transfers, as rates vary by region.</span></span></p></td>
<td><span data-ttu-id="23587-313">Asien-Pazifik, Europa, Lateinamerika, Nordamerika</span><span class="sxs-lookup"><span data-stu-id="23587-313">Asia Pacific, Europe, Latin America, North America</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="23587-314">SKU</span><span class="sxs-lookup"><span data-stu-id="23587-314">SKU</span></span></td>
<td><p><span data-ttu-id="23587-315">MSFT eindeutiger Bezeichner für das Angebot</span><span class="sxs-lookup"><span data-stu-id="23587-315">MSFT unique identifier for offer</span></span></p></td>
<td><span data-ttu-id="23587-316">7UD 00001</span><span class="sxs-lookup"><span data-stu-id="23587-316">7UD-00001</span></span></td>
</tr>
<tr class="odd">
<td><p><span data-ttu-id="23587-317">DetailLineItemId</span><span class="sxs-lookup"><span data-stu-id="23587-317">DetailLineItemId</span></span></p></td>
<td><p><span data-ttu-id="23587-318">Eine ID und Menge für die Angabe der verschiedenen Preise für einen Dienst oder eine Ressource in einem bestimmten Abrechnungszeitraum.</span><span class="sxs-lookup"><span data-stu-id="23587-318">An ID and quantity for itemizing the different rates for a service or resource in a given billing period.</span></span> <span data-ttu-id="23587-319">Für abgestufte Raten für Azure wird möglicherweise eine Rate für eine bestimmte Menge von berechenbare Einheiten berechnet und eine andere Rate danach.</span><span class="sxs-lookup"><span data-stu-id="23587-319">For Azure tiered rating, there may be one rate up to a certain quantity of billable units, then a different rate after that.</span></span></p></td>
<td><span data-ttu-id="23587-320">1</span><span class="sxs-lookup"><span data-stu-id="23587-320">1</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="23587-321">ConsumedQuantity</span><span class="sxs-lookup"><span data-stu-id="23587-321">ConsumedQuantity</span></span></td>
<td><p><span data-ttu-id="23587-322">Der Betrag für genutzte Dienste (Stunden, GB usw.) während des Berichtszeitraums.</span><span class="sxs-lookup"><span data-stu-id="23587-322">The amount of service consumed (hours, GB, etc.) during the reporting period.</span></span></p>
<p><span data-ttu-id="23587-323">Enthält außerdem jede nicht berechnete Nutzung aus dem vorherigen Berichtszeitraum.</span><span class="sxs-lookup"><span data-stu-id="23587-323">Also includes any unbilled usage from previous reporting periods.</span></span></p></td>
<td><span data-ttu-id="23587-324">11</span><span class="sxs-lookup"><span data-stu-id="23587-324">11</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="23587-325">IncludedQuantity</span><span class="sxs-lookup"><span data-stu-id="23587-325">IncludedQuantity</span></span></td>
<td><p><span data-ttu-id="23587-326">Enthaltene Einheiten als Teil des Angebots.</span><span class="sxs-lookup"><span data-stu-id="23587-326">Units included as part of the offer.</span></span> <span data-ttu-id="23587-327">In der Regel nicht im CSP vorhanden.</span><span class="sxs-lookup"><span data-stu-id="23587-327">Not typically present in CSP.</span></span></p></td>
<td><span data-ttu-id="23587-328">0</span><span class="sxs-lookup"><span data-stu-id="23587-328">0</span></span></td>
</tr>
<tr class="even">
<td><p><span data-ttu-id="23587-329">OverageQuantity</span><span class="sxs-lookup"><span data-stu-id="23587-329">OverageQuantity</span></span></p></td>
<td><p><span data-ttu-id="23587-330">Einheiten, die nicht Teil des Angebots sind und vom Partner bezahlt werden müssen.</span><span class="sxs-lookup"><span data-stu-id="23587-330">Units not included as part of the offer, that must be paid for by the partner.</span></span></p>
<p><span data-ttu-id="23587-331">Gleich ConsumedQuantity - IncludedQuantity.</span><span class="sxs-lookup"><span data-stu-id="23587-331">Equal to the ConsumedQuantity - IncludedQuantity.</span></span></p></td>
<td><span data-ttu-id="23587-332">11</span><span class="sxs-lookup"><span data-stu-id="23587-332">11</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="23587-333">ListPrice</span><span class="sxs-lookup"><span data-stu-id="23587-333">ListPrice</span></span></td>
<td><p><span data-ttu-id="23587-334">Gültiger Angebotspreis ab Anfangsdatum des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="23587-334">Offer price in effect at subscription start date.</span></span></p></td>
<td><span data-ttu-id="23587-335">0,0808 $</span><span class="sxs-lookup"><span data-stu-id="23587-335">$0.0808</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="23587-336">PretaxCharges</span><span class="sxs-lookup"><span data-stu-id="23587-336">PretaxCharges</span></span></td>
<td><p><span data-ttu-id="23587-337">ListPrist mal OverageQuantity, auf den nächsten Cent gerundet.</span><span class="sxs-lookup"><span data-stu-id="23587-337">ListPrist times OverageQuantity, rounded to the nearest cent.</span></span></p></td>
<td><span data-ttu-id="23587-338">0,085 $</span><span class="sxs-lookup"><span data-stu-id="23587-338">$0.085</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="23587-339">TaxAmount</span><span class="sxs-lookup"><span data-stu-id="23587-339">TaxAmount</span></span></td>
<td><p><span data-ttu-id="23587-340">USt.-Betrag auf der Grundlage der Steuervorschriften und spezifischen Gegebenheiten Ihres Markts.</span><span class="sxs-lookup"><span data-stu-id="23587-340">Tax amount charge, based on your market's tax rules and specific circumstances.</span></span></p></td>
<td><span data-ttu-id="23587-341">0,08 $</span><span class="sxs-lookup"><span data-stu-id="23587-341">$0.08</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="23587-342">PostTaxTotal</span><span class="sxs-lookup"><span data-stu-id="23587-342">PostTaxTotal</span></span></td>
<td><p><span data-ttu-id="23587-343">Gesamtbetrag nach Steuern, wo Steuern berechnet werden.</span><span class="sxs-lookup"><span data-stu-id="23587-343">Total after tax, when tax is applicable.</span></span></p></td>
<td><span data-ttu-id="23587-344">0,93 $</span><span class="sxs-lookup"><span data-stu-id="23587-344">$0.93</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="23587-345">Währung</span><span class="sxs-lookup"><span data-stu-id="23587-345">Currency</span></span></td>
<td><p><span data-ttu-id="23587-346">Währungstyp</span><span class="sxs-lookup"><span data-stu-id="23587-346">Currency type.</span></span> <span data-ttu-id="23587-347">Jede Abrechnungsentität verfügt nur über eine Währung.</span><span class="sxs-lookup"><span data-stu-id="23587-347">Each billing entity has only one currency.</span></span> <span data-ttu-id="23587-348">Überprüft auf Übereinstimmung in Ihrer ersten Rechnung und nach jedem großen Update der Abrechnungsplattform.</span><span class="sxs-lookup"><span data-stu-id="23587-348">Check that it matches your first invoice and then after any major billing platform update.</span></span></p></td>
<td><span data-ttu-id="23587-349">CNY</span><span class="sxs-lookup"><span data-stu-id="23587-349">CNY</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="23587-350">PretaxEffectiveRate</span><span class="sxs-lookup"><span data-stu-id="23587-350">PretaxEffectiveRate</span></span></td>
<td><p><span data-ttu-id="23587-351">Nettopreis pro Einheit.</span><span class="sxs-lookup"><span data-stu-id="23587-351">Pretax price per unit.</span></span> <span data-ttu-id="23587-352">Gleich PretaxCharges / OverageQuantity, auf den nächsten Cent gerundet.</span><span class="sxs-lookup"><span data-stu-id="23587-352">Equal to PretaxCharges / OverageQuantity, rounded to the nearest cent.</span></span></p></td>
<td><span data-ttu-id="23587-353">0,08 $</span><span class="sxs-lookup"><span data-stu-id="23587-353">$0.08</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="23587-354">PostTaxEffectiveRate</span><span class="sxs-lookup"><span data-stu-id="23587-354">PostTaxEffectiveRate</span></span></td>
<td><p><span data-ttu-id="23587-355">Bruttopreis pro Einheit.</span><span class="sxs-lookup"><span data-stu-id="23587-355">Post tax price per unit.</span></span> <span data-ttu-id="23587-356">Gleich PostTaxTotal / OverageQuantity oder PretaxEffectiveRate + Steuersatz pro Einheit, auf den nächsten Cent gerundet.</span><span class="sxs-lookup"><span data-stu-id="23587-356">Equal to PostTaxTotal / OverageQuantity, or PretaxEffectiveRate + tax rate per unit amoun, rounded to the nearest cent.</span></span></p></td>
<td><span data-ttu-id="23587-357">0,08 $</span><span class="sxs-lookup"><span data-stu-id="23587-357">$0.08</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="23587-358">ChargeType</span><span class="sxs-lookup"><span data-stu-id="23587-358">ChargeType</span></span></td>
<td><p><span data-ttu-id="23587-359">Art der Gebühren oder der Anpassungen.</span><span class="sxs-lookup"><span data-stu-id="23587-359">The type of charge or adjustment.</span></span> <span data-ttu-id="23587-360">Siehe <a href="#charge_types">Zuordnung von Gebühren zwischen einer Rechnung und der Erstattungsdatei</a></span><span class="sxs-lookup"><span data-stu-id="23587-360">See <a href="#charge_types">Mapping charges between an invoice and the reconciliation file</a></span></span></p></td>
<td><p><span data-ttu-id="23587-361">Siehe <a href="#charge_types">Zuordnung von Gebühren zwischen einer Rechnung und der Erstattungsdatei</a></span><span class="sxs-lookup"><span data-stu-id="23587-361">See <a href="#charge_types">Mapping charges between an invoice and the reconciliation file</a></span></span></p></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="23587-362">CustomerBillableAccount</span><span class="sxs-lookup"><span data-stu-id="23587-362">CustomerBillableAccount</span></span></td>
<td><p><span data-ttu-id="23587-363">Eindeutige Konto-ID auf der MSFT-Abrechnungsplattform.</span><span class="sxs-lookup"><span data-stu-id="23587-363">Unique account ID in the MSFT billing platform.</span></span></p></td>
<td><span data-ttu-id="23587-364">1280018095</span><span class="sxs-lookup"><span data-stu-id="23587-364">1280018095</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="23587-365">UsageDate</span><span class="sxs-lookup"><span data-stu-id="23587-365">UsageDate</span></span></td>
<td><p><span data-ttu-id="23587-366">Datum der Service-Bereitstellung.</span><span class="sxs-lookup"><span data-stu-id="23587-366">Date of service deployment.</span></span></p></td>
<td><span data-ttu-id="23587-367">01.02.2014 0:00</span><span class="sxs-lookup"><span data-stu-id="23587-367">2/1/2014 0:00</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="23587-368">MeteredRegion</span><span class="sxs-lookup"><span data-stu-id="23587-368">MeteredRegion</span></span></td>
<td><p><span data-ttu-id="23587-369">Diese Spalte gibt den Standort eines Rechenzentrums in der Region für die Dienste an, auf die dies zutrifft.</span><span class="sxs-lookup"><span data-stu-id="23587-369">This column identifies the location of a data center within the region for services where this is applicable and populated.</span></span></p></td>
<td><span data-ttu-id="23587-370">Ostasien, Südostasien, Nordeuropa, Westeuropa, USA (Mitte/Norden), USA (Mitte/Süden)</span><span class="sxs-lookup"><span data-stu-id="23587-370">East Asia, South East Asia, North Europe, West Europe, North Central US, South Central US</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="23587-371">MeteredService</span><span class="sxs-lookup"><span data-stu-id="23587-371">MeteredService</span></span></td>
<td><p><span data-ttu-id="23587-372">Diese Spalte wird verwendet, um den einzelnen Microsoft Azure-Dienst zu verfolgen, der in der Spalte mit dem Dienstnamen möglicherweise nicht eindeutig identifiziert ist.</span><span class="sxs-lookup"><span data-stu-id="23587-372">This column is utilized to track the individual Microsoft Azure service that may not be specifically identified in the Service Name column.</span></span> <span data-ttu-id="23587-373">Beispielsweise werden Datenübertragungen als &quot;Microsoft Azure – Alle Dienste&quot; in der Dienstnamenspalte angegeben.</span><span class="sxs-lookup"><span data-stu-id="23587-373">For example, data transfers are reported as &quot;Microsoft Azure - All Services&quot; in the Service Name column.</span></span> <span data-ttu-id="23587-374">In der Spalte „MeteredService“ wird angegeben, auf welchen Dienst sich die Nutzung jeweils bezieht.</span><span class="sxs-lookup"><span data-stu-id="23587-374">This MeteredService column will indicate to which specific service the usage pertains.</span></span></p></td>
<td><span data-ttu-id="23587-375">AccessControl, CDN, Computing, Datenbank, ServiceBus, Speicher</span><span class="sxs-lookup"><span data-stu-id="23587-375">AccessControl, CDN, Compute, Database, ServiceBus, Storage</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="23587-376">MeteredServiceType</span><span class="sxs-lookup"><span data-stu-id="23587-376">MeteredServiceType</span></span></td>
<td><p><span data-ttu-id="23587-377">Eine Unterüberschrift, die den einzelnen Microsoft Azure-Dienst jenseits der Stufe weiter erläutert, die im Feld „MeteredService” bereitgestellt wird.</span><span class="sxs-lookup"><span data-stu-id="23587-377">A subheading that further clarifies the individual Microsoft Azure service beyond the level provided by the MeteredService field.</span></span></p></td>
<td><span data-ttu-id="23587-378">EXTERN</span><span class="sxs-lookup"><span data-stu-id="23587-378">EXTERNAL</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="23587-379">Projekt</span><span class="sxs-lookup"><span data-stu-id="23587-379">Project</span></span></td>
<td><p><span data-ttu-id="23587-380">Vom Kunden definierter Name für die Dienstinstanz</span><span class="sxs-lookup"><span data-stu-id="23587-380">Customer-defined name for their service instance</span></span></p></td>
<td><span data-ttu-id="23587-381">ORDDC52E52FDEF405786F0642DD0108BE4</span><span class="sxs-lookup"><span data-stu-id="23587-381">ORDDC52E52FDEF405786F0642DD0108BE4</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="23587-382">ServiceInfo</span><span class="sxs-lookup"><span data-stu-id="23587-382">ServiceInfo</span></span></td>
<td><p><span data-ttu-id="23587-383">Die Anzahl der ServiceBus-Verbindungen, die bereitgestellt und an einem bestimmten Tag genutzt wurden.</span><span class="sxs-lookup"><span data-stu-id="23587-383">The number of ServiceBus connections that were provisioned and utilized on a given day.</span></span></p></td>
<td><span data-ttu-id="23587-384">Beispiel: Wenn Sie während eines Monats mit 30 Tagen über eine individuell bereitgestellte Verbindung verfügen, wird für Service Info 1 „1,000000 Verbindungen/30 Tage” angegeben.</span><span class="sxs-lookup"><span data-stu-id="23587-384">For example: if you had an individually provisioned connection during a 30 day month, Service Info 1 would read “1.000000 Connections / 30 days”.</span></span> <span data-ttu-id="23587-385">Wenn Sie ein 25-Paket von Service Bus-Verbindungen, die bereitgestellt mussten, und Sie haben 1 während des Tages verwendet, würde Ihre Anweisung zur täglichen Nutzung für diesen Tag angeben "25 Verbindungen / 30 Tage – verwendet: 1.000000”.</span><span class="sxs-lookup"><span data-stu-id="23587-385">If you had a 25 pack of ServiceBus connections provisioned and you had utilized 1 during that day, your daily usage statement for that day would indicate “25 Connections / 30 Days – Used: 1.000000”.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="23587-386">CustomerID</span><span class="sxs-lookup"><span data-stu-id="23587-386">CustomerID</span></span></td>
<td><p><span data-ttu-id="23587-387">Eindeutige Microsoft-ID im GUID-Format: wird zur Identifizierung des Kunden verwendet.</span><span class="sxs-lookup"><span data-stu-id="23587-387">Unique Microsoft ID, in GUID format, used to identify the customer.</span></span></p></td>
<td><span data-ttu-id="23587-388">ORDDC52E52FDEF405786F0642DD0108BE4</span><span class="sxs-lookup"><span data-stu-id="23587-388">ORDDC52E52FDEF405786F0642DD0108BE4</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="23587-389">DomainName</span><span class="sxs-lookup"><span data-stu-id="23587-389">DomainName</span></span></td>
<td><p><span data-ttu-id="23587-390">Kundendomänenname: wird zur Identifizierung des Kunden verwendet.</span><span class="sxs-lookup"><span data-stu-id="23587-390">Customer's domain name, used to help identify the customer.</span></span></p></td>
<td><span data-ttu-id="23587-391">example.onmicrosoft.com</span><span class="sxs-lookup"><span data-stu-id="23587-391">example.onmicrosoft.com</span></span></td></tr>
</tbody>
</table>



## <a href="" id="charge_types"></a><span data-ttu-id="23587-392">Zuordnung der Gebühren zwischen Rechnung und abstimmungsdatei</span><span class="sxs-lookup"><span data-stu-id="23587-392">Mapping charges between an invoice and the reconciliation file</span></span>

<span data-ttu-id="23587-393">Ihre Rechnung enthält eine Zusammenfassung der Gebühren, während die Erstattungsdatei eine detaillierte Aufschlüsselung der Positionstransaktionen bereitstellt, einschließlich der Gebührentypen.</span><span class="sxs-lookup"><span data-stu-id="23587-393">Your invoice provides a summary of charges, while your reconciliation file provides a detailed breakdown of line-item transactions, including charge types.</span></span>

<span data-ttu-id="23587-394">Zum Erstellen von Querverweisen der Gebührenbeträge zwischen der Rechnung und der Abstimmungsdatei können Sie Microsoft Excel-Filteroptionen verwenden, indem Sie in der Erstattungsdatei nach Gebührentypen filtern, um die Rechnungsgebühren einer Reihe von Gebührenauflistungen in der Erstattungsdatei zuzuordnen.</span><span class="sxs-lookup"><span data-stu-id="23587-394">To cross-reference charge amounts between the invoice and reconciliation file, you can use Microsoft Excel's filter options to filter by charge types on the reconciliation file to map the invoice charges to a set of charge breakdowns on reconciliation file.</span></span>

<span data-ttu-id="23587-395">Die folgende Tabelle zeigt die Zuordnungen zwischen einem Rechnungsabschnitt und zugehörigen Gebührentypen, die möglicherweise auf den Erstattungsdateien angezeigt werden.</span><span class="sxs-lookup"><span data-stu-id="23587-395">The table below shows the mappings between an invoice section and associated charge types that might show up on the reconciliation files.</span></span> 

<table>
<tbody>
<tr>
<td>
<p><span data-ttu-id="23587-396"><strong>Beschreibung der Rechnungsgebühren</strong></span><span class="sxs-lookup"><span data-stu-id="23587-396"><strong>Invoice charge description</strong></span></span></p>
</td>
<td>
<p><span data-ttu-id="23587-397"><strong>Abstimmung DateiBeschreibung (ChargeType-Spalte)</strong></span><span class="sxs-lookup"><span data-stu-id="23587-397"><strong>Reconciliation file charge description (ChargeType column)</strong></span></span></p>
</td>
<td>
<p><span data-ttu-id="23587-398"><strong>Was diese Gebühr ist?</strong></span><span class="sxs-lookup"><span data-stu-id="23587-398"><strong>What is this charge?</strong></span></span></p>
</td>
<td>
<p><span data-ttu-id="23587-399"><strong>Wie ordne ich dieser Gebührentypen zur Rechnung zu?</strong></span><span class="sxs-lookup"><span data-stu-id="23587-399"><strong>How do I map these ChargeTypes to the invoice?</strong></span></span></p>
</td>
</tr>
<tr>
<td rowspan="8">
<p><span data-ttu-id="23587-400"><strong>Laufende Gebühren</strong></span><span class="sxs-lookup"><span data-stu-id="23587-400"><strong>Recurring Charges</strong></span></span></p>
</td>
<td>
<p><span data-ttu-id="23587-401">Instanz anteilig stornieren</span><span class="sxs-lookup"><span data-stu-id="23587-401">Cancel instance prorate</span></span></p>
</td>
<td>
<p><span data-ttu-id="23587-402">Anteilige Gebühren werden an den Kunden zurückerstattet, wenn verknüpfte Lizenzen geändert werden.</span><span class="sxs-lookup"><span data-stu-id="23587-402">Prorated charges refunded to the customer when associated seats are changed</span></span></p>
</td>
<td rowspan="8">
<p><span data-ttu-id="23587-403">Erstellen Sie in der lizenzbasierten Datei die Summe der Spalte <strong>Betrag</strong>.</span><span class="sxs-lookup"><span data-stu-id="23587-403">From license-based file, sum the <strong>Amount</strong> column</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="23587-404">Gebühr für Zyklus</span><span class="sxs-lookup"><span data-stu-id="23587-404">Cycle fee</span></span></p>
</td>
<td>
<p><span data-ttu-id="23587-405">Periodische Gebühren für ein Abonnement</span><span class="sxs-lookup"><span data-stu-id="23587-405">Periodic charges for a subscription</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="23587-406">Anteiliger Zyklus für Instanz</span><span class="sxs-lookup"><span data-stu-id="23587-406">Cycle instance prorate</span></span></p>
</td>
<td>
<p><span data-ttu-id="23587-407">Anteilige vom Kunden geschätzte Gebühren, wenn verknüpfte Lizenzen geändert werden</span><span class="sxs-lookup"><span data-stu-id="23587-407">Prorated charges assessed from the customer when associated seats are changed</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="23587-408">Gebühren bei Abbrechen anteilig zuordnen</span><span class="sxs-lookup"><span data-stu-id="23587-408">Prorate fees when cancel</span></span></p>
</td>
<td>
<p><span data-ttu-id="23587-409">Anteilige Erstattung für nicht verwendete Teile des Diensts bei einer Stornierung</span><span class="sxs-lookup"><span data-stu-id="23587-409">Prorated refund for unused portion of service upon cancellation</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="23587-410">Anteilige Gebühren beim Kauf</span><span class="sxs-lookup"><span data-stu-id="23587-410">Prorate fees when purchase</span></span></p>
</td>
<td>
<p><span data-ttu-id="23587-411">Anteilige Gebühren beim Kauf</span><span class="sxs-lookup"><span data-stu-id="23587-411">Prorated fees upon purchase</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="23587-412">Kaufgebühr</span><span class="sxs-lookup"><span data-stu-id="23587-412">Purchase fee</span></span></p>
</td>
<td>
<p><span data-ttu-id="23587-413">Anfängliche Gebühr für ein Abonnement</span><span class="sxs-lookup"><span data-stu-id="23587-413">Initial charge for a subscription</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="23587-414">Anteilige Gebühr bei Verlängerung</span><span class="sxs-lookup"><span data-stu-id="23587-414">Prorate fee when renew</span></span></p>
</td>
<td>
<p><span data-ttu-id="23587-415">Anteilige Gebühren nach Verlängerung des Abonnements</span><span class="sxs-lookup"><span data-stu-id="23587-415">Prorated fees upon subscription renewal</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="23587-416">Verlängerungsgebühr</span><span class="sxs-lookup"><span data-stu-id="23587-416">Renew fee</span></span></p>
</td>
<td>
<p><span data-ttu-id="23587-417">Gebühr für Verlängerung eines Abonnements</span><span class="sxs-lookup"><span data-stu-id="23587-417">Charge for renewing a subscription</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="23587-418"><strong>Andere Produkte und Dienste</strong></span><span class="sxs-lookup"><span data-stu-id="23587-418"><strong>Other Products and Services</strong></span></span></p>
</td>
<td>
<p><span data-ttu-id="23587-419">Anteilige Gebühren beim Aktivieren</span><span class="sxs-lookup"><span data-stu-id="23587-419">Prorate fees when activate</span></span></p>
</td>
<td>
<p><span data-ttu-id="23587-420">Anteilige Gebühren bei Aktivierung bis zum Ende des Abrechnungszeitraums</span><span class="sxs-lookup"><span data-stu-id="23587-420">Prorated fees from activation until end of billing period</span></span></p>
</td>
<td>
<p><span data-ttu-id="23587-421">Erstellen Sie in der lizenzbasierten Datei die Summe der Spalte <strong>Betrag</strong>.</span><span class="sxs-lookup"><span data-stu-id="23587-421">From license-based file, sum the <strong>Amount</strong> column</span></span></p>
</td>
</tr>
<tr>
<td rowspan="2">
<p><span data-ttu-id="23587-422"><strong>Nutzungsgebühren</strong></span><span class="sxs-lookup"><span data-stu-id="23587-422"><strong>Usage Charges</strong></span></span></p>
</td>
<td>
<p><span data-ttu-id="23587-423">Nutzungsgebühr beim Abbrechen bewerten</span><span class="sxs-lookup"><span data-stu-id="23587-423">Assess usage fee when cancel</span></span></p>
</td>
<td>
<p><span data-ttu-id="23587-424">Nutzungsgebühr für Zugriffe für die nicht bezahlte Verwendung während des aktuellen Abrechnungszeitraums bei der Kündigung</span><span class="sxs-lookup"><span data-stu-id="23587-424">Access usage fee upon cancellation for unpaid usage during the current billing period</span></span></p>
</td>
<td rowspan="2">
<p><span data-ttu-id="23587-425">Erstellen Sie in der nutzungsbasierten Datei die Summe der Spalte <strong>PretaxCharges</strong>.</span><span class="sxs-lookup"><span data-stu-id="23587-425">From usage-based file, sum the <strong>PretaxCharges</strong> column</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="23587-426">Nutzungsgebühr für den aktuellen Zyklus bewerten</span><span class="sxs-lookup"><span data-stu-id="23587-426">Assess usage fee for current cycle</span></span></p>
</td>
<td>
<p><span data-ttu-id="23587-427">Zugriffsnutzungsgebühr für den aktuellen Abrechnungszeitraum</span><span class="sxs-lookup"><span data-stu-id="23587-427">Access usage fee for the current billing period</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="23587-428"><strong>Gutschriften &amp; Anpassungen</strong></span><span class="sxs-lookup"><span data-stu-id="23587-428"><strong>Credits &amp; Adjustments</strong></span></span></p>
</td>
<td>
<p><span data-ttu-id="23587-429">Einen Artikel versetzen</span><span class="sxs-lookup"><span data-stu-id="23587-429">Offset a line item</span></span></p>
</td>
<td>
<p><span data-ttu-id="23587-430">Teilweise oder vollständige Erstattung an eine Position, einschließlich Steuern</span><span class="sxs-lookup"><span data-stu-id="23587-430">Partial or whole refund to a line item, including taxes</span></span></p>
</td>
<td>
<p><span data-ttu-id="23587-431">Erstellen Sie in der lizenzbasierten Datei die Summe der Spalte <strong>TotalForCustomer</strong>.</span><span class="sxs-lookup"><span data-stu-id="23587-431">From license-based file, sum the <strong>TotalForCustomer</strong> column</span></span></p>
<p><span data-ttu-id="23587-432">Erstellen Sie in der nutzungsbasierten Datei die Summe der Spalte <strong>PostTaxTotal</strong>.</span><span class="sxs-lookup"><span data-stu-id="23587-432">From usage-based file, sum the <strong>PostTaxTotal</strong> column</span></span></p>
</td>
</tr>


<tr>
<td rowspan="4">
<p><span data-ttu-id="23587-433"><strong>Sonstige Rabatte</strong></span><span class="sxs-lookup"><span data-stu-id="23587-433"><strong>Other Discounts</strong></span></span></br><span data-ttu-id="23587-434">
<em>(usage-based)</em></span><span class="sxs-lookup"><span data-stu-id="23587-434">
<em>(usage-based)</em></span></span></p>
</td>
<td>
<p><span data-ttu-id="23587-435">Aktivierungsrabatt</span><span class="sxs-lookup"><span data-stu-id="23587-435">Activation discount</span></span></p>
</td>
<td>
<p><span data-ttu-id="23587-436">Rabatt auf Aktivierung des Abonnements</span><span class="sxs-lookup"><span data-stu-id="23587-436">Discount applied when subscription activated</span></span></p>
</td>
<td rowspan="4">
<p><span data-ttu-id="23587-437">Erstellen Sie in der nutzungsbasierten Datei die Summe der Spalte <strong>PretaxCharges</strong>.</span><span class="sxs-lookup"><span data-stu-id="23587-437">From usage-based file, sum the <strong>PretaxCharges</strong> column</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="23587-438">Zyklusrabatt</span><span class="sxs-lookup"><span data-stu-id="23587-438">Cycle discount</span></span></p>
</td>
<td>
<p><span data-ttu-id="23587-439">Rabatt auf periodische Gebühren</span><span class="sxs-lookup"><span data-stu-id="23587-439">Discount applied on periodic charges</span></span></p>
</td>
</tr><tr>
<td>
<p><span data-ttu-id="23587-440">Verlängerungsrabatt</span><span class="sxs-lookup"><span data-stu-id="23587-440">Renew discount</span></span></p>
</td>
<td>
<p><span data-ttu-id="23587-441">Rabatt auf Verlängerung des Abonnements</span><span class="sxs-lookup"><span data-stu-id="23587-441">Discount applied when subscription renewed</span></span></p>
</td>
</tr><tr>
<td>
<p><span data-ttu-id="23587-442">Stornorabatt</span><span class="sxs-lookup"><span data-stu-id="23587-442">Cancel discount</span></span></p>
</td>
<td>
<p><span data-ttu-id="23587-443">Gebühren, wenn Rabatte storniert werden</span><span class="sxs-lookup"><span data-stu-id="23587-443">Charges applied when discounts cancelled</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="23587-444"><strong>Sonstige Rabatte</strong></span><span class="sxs-lookup"><span data-stu-id="23587-444"><strong>Other Discounts</strong></span></span></br><span data-ttu-id="23587-445">
<em>(Lizenz-basiert)</em></span><span class="sxs-lookup"><span data-stu-id="23587-445">
<em>(license-based)</em></span></span></p>
</td>
<td>
<p><span data-ttu-id="23587-446"><em>Kann für mehrere gebührentypen angewendet werden</em></span><span class="sxs-lookup"><span data-stu-id="23587-446"><em>May be applied to multiple charge types</em></span></span></p>
</td>
<td>
<p>&nbsp;</p>
</td>
<td>
<p><span data-ttu-id="23587-447">Erstellen Sie in der lizenzbasierten Datei die Summe der Spalte <strong>TotalOtherDiscount</strong>.</span><span class="sxs-lookup"><span data-stu-id="23587-447">From license-based file, sum the <strong>TotalOtherDiscount</strong> column</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="23587-448"><strong>Steuern</strong>&nbsp;oder&nbsp;<strong>Umsatzsteuer</strong></span><span class="sxs-lookup"><span data-stu-id="23587-448"><strong>Taxes</strong>&nbsp;or&nbsp;<strong>VAT</strong></span></span></p>
</td>
<td>
<p><span data-ttu-id="23587-449"><em>Kann für mehrere gebührentypen angewendet werden</em></span><span class="sxs-lookup"><span data-stu-id="23587-449"><em>May be applied to multiple charge types</em></span></span></p>
<p><span data-ttu-id="23587-450"><em>Ausnahme: "Ausgleich einer Position" Steuer bereits enthalten. Rechtliche Hinweise &amp; Anpassungen weiter oben.</em></span><span class="sxs-lookup"><span data-stu-id="23587-450"><em>Exception: "Offset a line item" already includes taxes. See Credits &amp; Adjustments, above.</em></span></span></p>
</td>
<td>
<p><span data-ttu-id="23587-451">Steuern oder Umsatzsteuern (Umsatzsteuer)</span><span class="sxs-lookup"><span data-stu-id="23587-451">Taxes or value-added taxes (VAT)</span></span></p>
</td>
<td>
<p><span data-ttu-id="23587-452">Erstellen Sie in der lizenzbasierten Datei die Summe der Spalte <strong>Steuern</strong>.</span><span class="sxs-lookup"><span data-stu-id="23587-452">From license-based file, sum the <strong>Tax</strong> column</span></span></p>
<p><span data-ttu-id="23587-453">Erstellen Sie in der nutzungsbasierten Datei die Summe der Spalte <strong>TaxAmount</strong>.</span><span class="sxs-lookup"><span data-stu-id="23587-453">From usage-based file, sum the <strong>TaxAmount</strong> column</span></span></p>
</td>
</tr>
</tbody>
</table>
<p>&nbsp;</p>