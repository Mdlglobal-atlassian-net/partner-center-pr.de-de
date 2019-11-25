---
title: Usage-based reconciliation files | Partner Center
ms.topic: article
ms.date: 11/21/2019
description: Understand usage-based reconciliation files in Partner Center.
ms.assetid: ''
author: LauraBrenner
ms.author: labrenne
ms.localizationpriority: medium
ms.openlocfilehash: 3cf0f20ed266fa5302264ef07092d47c050a9206
ms.sourcegitcommit: 1c3d3b95135e1daad5ba5585a090e84ab0b97594
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 11/22/2019
ms.locfileid: "74389778"
---
# <a name="usage-based-file-fields"></a><span data-ttu-id="58864-103">Nutzungsbasierte Dateifelder</span><span class="sxs-lookup"><span data-stu-id="58864-103">Usage-based file fields</span></span>

<span data-ttu-id="58864-104">Betrifft</span><span class="sxs-lookup"><span data-stu-id="58864-104">Applies to:</span></span>

- <span data-ttu-id="58864-105">Partner Center</span><span class="sxs-lookup"><span data-stu-id="58864-105">Partner Center</span></span>
- <span data-ttu-id="58864-106">Partner Center für Microsoft Cloud for US Government</span><span class="sxs-lookup"><span data-stu-id="58864-106">Partner Center for Microsoft Cloud for US Government</span></span>

<span data-ttu-id="58864-107">To reconcile your charges against a customer's usage, compare the **ResellerID**, **ResellerName**, and **ResellerBillableAccount** from the reconciliation file with the **Customer name** and **Subscription ID** from Partner Center.</span><span class="sxs-lookup"><span data-stu-id="58864-107">To reconcile your charges against a customer's usage, compare the **ResellerID**, **ResellerName**, and **ResellerBillableAccount** from the reconciliation file with the **Customer name** and **Subscription ID** from Partner Center.</span></span>

## <a name="fields-in-usage-based-reconciliation-files"></a><span data-ttu-id="58864-108">Fields in usage-based reconciliation files</span><span class="sxs-lookup"><span data-stu-id="58864-108">Fields in usage-based reconciliation files</span></span>

<span data-ttu-id="58864-109">Die folgenden Felder enthalten Informationen zu den verwendeten Diensten und den Raten.</span><span class="sxs-lookup"><span data-stu-id="58864-109">The following fields explain which services were used and the rate.</span></span>

| <span data-ttu-id="58864-110">Column</span><span class="sxs-lookup"><span data-stu-id="58864-110">Column</span></span> | <span data-ttu-id="58864-111">Beschreibung</span><span class="sxs-lookup"><span data-stu-id="58864-111">Description</span></span> | <span data-ttu-id="58864-112">Sample value(s)</span><span class="sxs-lookup"><span data-stu-id="58864-112">Sample value(s)</span></span> |
| ------ | ----------- | ------------ |
| <span data-ttu-id="58864-113">PartnerID</span><span class="sxs-lookup"><span data-stu-id="58864-113">PartnerID</span></span> | <span data-ttu-id="58864-114">Partner identifier, in GUID format.</span><span class="sxs-lookup"><span data-stu-id="58864-114">Partner identifier, in GUID format.</span></span> | <span data-ttu-id="58864-115">*DA41BC5F-C52D-4464-8A8D-8C8DCC43503B*</span><span class="sxs-lookup"><span data-stu-id="58864-115">*DA41BC5F-C52D-4464-8A8D-8C8DCC43503B*</span></span> |
| <span data-ttu-id="58864-116">PartnerName</span><span class="sxs-lookup"><span data-stu-id="58864-116">PartnerName</span></span> | <span data-ttu-id="58864-117">Partner name.</span><span class="sxs-lookup"><span data-stu-id="58864-117">Partner name.</span></span> | <span data-ttu-id="58864-118">*Contoso, Ltd.*</span><span class="sxs-lookup"><span data-stu-id="58864-118">*Contoso, Ltd.*</span></span> |
| <span data-ttu-id="58864-119">PartnerBillableAccountID</span><span class="sxs-lookup"><span data-stu-id="58864-119">PartnerBillableAccountID</span></span> | <span data-ttu-id="58864-120">Partner account identifier.</span><span class="sxs-lookup"><span data-stu-id="58864-120">Partner account identifier.</span></span> | <span data-ttu-id="58864-121">*1010578050*</span><span class="sxs-lookup"><span data-stu-id="58864-121">*1010578050*</span></span> |
| <span data-ttu-id="58864-122">CustomerName</span><span class="sxs-lookup"><span data-stu-id="58864-122">CustomerName</span></span> | <span data-ttu-id="58864-123">Customer's organization name, as reported in Partner Center.</span><span class="sxs-lookup"><span data-stu-id="58864-123">Customer's organization name, as reported in Partner Center.</span></span> <span data-ttu-id="58864-124">*Very important for reconciling the invoice with your system information.*</span><span class="sxs-lookup"><span data-stu-id="58864-124">*Very important for reconciling the invoice with your system information.*</span></span> | <span data-ttu-id="58864-125">*Test customer*</span><span class="sxs-lookup"><span data-stu-id="58864-125">*Test customer*</span></span> |
| <span data-ttu-id="58864-126">MPNID</span><span class="sxs-lookup"><span data-stu-id="58864-126">MPNID</span></span> | <span data-ttu-id="58864-127">MPN identifier of the CSP partner.</span><span class="sxs-lookup"><span data-stu-id="58864-127">MPN identifier of the CSP partner.</span></span> | <span data-ttu-id="58864-128">*4390934*</span><span class="sxs-lookup"><span data-stu-id="58864-128">*4390934*</span></span> |
| <span data-ttu-id="58864-129">ResellerMPNID</span><span class="sxs-lookup"><span data-stu-id="58864-129">ResellerMPNID</span></span> | <span data-ttu-id="58864-130">MPN identifier of the reseller of record for the subscription.</span><span class="sxs-lookup"><span data-stu-id="58864-130">MPN identifier of the reseller of record for the subscription.</span></span> <span data-ttu-id="58864-131">For more information, see [how to itemize by partner](use-the-reconciliation-files.md#itemize-reconciliation-files-by-partner).</span><span class="sxs-lookup"><span data-stu-id="58864-131">For more information, see [how to itemize by partner](use-the-reconciliation-files.md#itemize-reconciliation-files-by-partner).</span></span> | <span data-ttu-id="58864-132">*4390934*</span><span class="sxs-lookup"><span data-stu-id="58864-132">*4390934*</span></span> |
| <span data-ttu-id="58864-133">InvoiceNumber</span><span class="sxs-lookup"><span data-stu-id="58864-133">InvoiceNumber</span></span> | <span data-ttu-id="58864-134">Rechnungsnummer, in der die angegebene Transaktion angezeigt wird.</span><span class="sxs-lookup"><span data-stu-id="58864-134">Invoice number where the specified transaction appears.</span></span> | <span data-ttu-id="58864-135">*D020001IVK*</span><span class="sxs-lookup"><span data-stu-id="58864-135">*D020001IVK*</span></span> |
| <span data-ttu-id="58864-136">ChargeStartDate</span><span class="sxs-lookup"><span data-stu-id="58864-136">ChargeStartDate</span></span> | <span data-ttu-id="58864-137">Start date of billing cycle, except when presenting dates of previously uncharged latent usage data (from previous bill cycle).</span><span class="sxs-lookup"><span data-stu-id="58864-137">Start date of billing cycle, except when presenting dates of previously uncharged latent usage data (from previous bill cycle).</span></span> <span data-ttu-id="58864-138">Die Uhrzeit ist immer auf den Tagesbeginn um 0:00 Uhr festgelegt.</span><span class="sxs-lookup"><span data-stu-id="58864-138">The time is always the beginning of the day, 0:00.</span></span> | <span data-ttu-id="58864-139">*2/1/2019 0:00*</span><span class="sxs-lookup"><span data-stu-id="58864-139">*2/1/2019 0:00*</span></span> |
| <span data-ttu-id="58864-140">ChargeEndDate</span><span class="sxs-lookup"><span data-stu-id="58864-140">ChargeEndDate</span></span> | <span data-ttu-id="58864-141">End date of billing cycle, except when presenting dates of previously uncharged latent usage data (from previous bill cycle).</span><span class="sxs-lookup"><span data-stu-id="58864-141">End date of billing cycle, except when presenting dates of previously uncharged latent usage data (from previous bill cycle).</span></span> <span data-ttu-id="58864-142">Die Uhrzeit ist immer auf das Tagesende um 23:59 Uhr festgelegt.</span><span class="sxs-lookup"><span data-stu-id="58864-142">The time is always the end of the day, 23:59.</span></span> | <span data-ttu-id="58864-143">*2/28/2019 23:59*</span><span class="sxs-lookup"><span data-stu-id="58864-143">*2/28/2019 23:59*</span></span> |
| <span data-ttu-id="58864-144">SubscriptionID</span><span class="sxs-lookup"><span data-stu-id="58864-144">SubscriptionID</span></span> | <span data-ttu-id="58864-145">Eindeutiger Bezeichner für ein Abonnement auf der Microsoft-Abrechnungsplattform.</span><span class="sxs-lookup"><span data-stu-id="58864-145">Unique identifier for a subscription in the Microsoft billing platform.</span></span> <span data-ttu-id="58864-146">May be useful to identify the subscription when contacting support.</span><span class="sxs-lookup"><span data-stu-id="58864-146">May be useful to identify the subscription when contacting support.</span></span> <span data-ttu-id="58864-147">Not used for reconciliation.</span><span class="sxs-lookup"><span data-stu-id="58864-147">Not used for reconciliation.</span></span> <span data-ttu-id="58864-148">*This is not the same as the **Subscription ID** on the Partner Admin Console.*</span><span class="sxs-lookup"><span data-stu-id="58864-148">*This is not the same as the **Subscription ID** on the Partner Admin Console.*</span></span> | <span data-ttu-id="58864-149">*usCBMgAAAAAAAAIA*</span><span class="sxs-lookup"><span data-stu-id="58864-149">*usCBMgAAAAAAAAIA*</span></span> |
| <span data-ttu-id="58864-150">SubscriptionName</span><span class="sxs-lookup"><span data-stu-id="58864-150">SubscriptionName</span></span> | <span data-ttu-id="58864-151">Nickname for the service offering.</span><span class="sxs-lookup"><span data-stu-id="58864-151">Nickname for the service offering.</span></span> | <span data-ttu-id="58864-152">*Microsoft Azure*</span><span class="sxs-lookup"><span data-stu-id="58864-152">*Microsoft Azure*</span></span> |
| <span data-ttu-id="58864-153">SubscriptionDescription</span><span class="sxs-lookup"><span data-stu-id="58864-153">SubscriptionDescription</span></span> | <span data-ttu-id="58864-154">Line of business of the service offering.</span><span class="sxs-lookup"><span data-stu-id="58864-154">Line of business of the service offering.</span></span> | <span data-ttu-id="58864-155">*Microsoft Azure*</span><span class="sxs-lookup"><span data-stu-id="58864-155">*Microsoft Azure*</span></span> |
| <span data-ttu-id="58864-156">OrderID</span><span class="sxs-lookup"><span data-stu-id="58864-156">OrderID</span></span> | <span data-ttu-id="58864-157">Eindeutiger Bezeichner für eine Bestellung auf der Microsoft-Abrechnungsplattform.</span><span class="sxs-lookup"><span data-stu-id="58864-157">Unique identifier for an order in the Microsoft billing platform.</span></span> <span data-ttu-id="58864-158">May be useful to identify the subscription when contacting support.</span><span class="sxs-lookup"><span data-stu-id="58864-158">May be useful to identify the subscription when contacting support.</span></span> <span data-ttu-id="58864-159">Not used for reconciliation.</span><span class="sxs-lookup"><span data-stu-id="58864-159">Not used for reconciliation.</span></span> | <span data-ttu-id="58864-160">*566890604832738111*</span><span class="sxs-lookup"><span data-stu-id="58864-160">*566890604832738111*</span></span> |
| <span data-ttu-id="58864-161">ServiceName</span><span class="sxs-lookup"><span data-stu-id="58864-161">ServiceName</span></span> | <span data-ttu-id="58864-162">Der Name des fraglichen Azure-Dienstes</span><span class="sxs-lookup"><span data-stu-id="58864-162">The name of the Azure service in question.</span></span> | <span data-ttu-id="58864-163">*VIRTUAL MACHINES*</span><span class="sxs-lookup"><span data-stu-id="58864-163">*VIRTUAL MACHINES*</span></span> |
| <span data-ttu-id="58864-164">ServiceType</span><span class="sxs-lookup"><span data-stu-id="58864-164">ServiceType</span></span> | <span data-ttu-id="58864-165">The specific type of Azure service.</span><span class="sxs-lookup"><span data-stu-id="58864-165">The specific type of Azure service.</span></span> | <span data-ttu-id="58864-166">*Service Bus – Individual or Pack*, *SQL Azure database – Business or Web Edition*</span><span class="sxs-lookup"><span data-stu-id="58864-166">*Service Bus – Individual or Pack*, *SQL Azure database – Business or Web Edition*</span></span> |
| <span data-ttu-id="58864-167">ResourceGUID</span><span class="sxs-lookup"><span data-stu-id="58864-167">ResourceGUID</span></span> | <span data-ttu-id="58864-168">Bestimmter eindeutiger Bezeichner für alle Dienstdaten und die Preisstruktur.</span><span class="sxs-lookup"><span data-stu-id="58864-168">Specific unique identifier for all the service data and pricing structure.</span></span> | <span data-ttu-id="58864-169">*DA41BC5F-C52D-4464-8A8D-8C8DCC43503B*</span><span class="sxs-lookup"><span data-stu-id="58864-169">*DA41BC5F-C52D-4464-8A8D-8C8DCC43503B*</span></span> |
| <span data-ttu-id="58864-170">Ressourcenname</span><span class="sxs-lookup"><span data-stu-id="58864-170">ResourceName</span></span> | <span data-ttu-id="58864-171">Der Name der Azure-Ressource.</span><span class="sxs-lookup"><span data-stu-id="58864-171">The name of the Azure resource.</span></span> | <span data-ttu-id="58864-172">*Data Transfer In (GB)* , *Data Transfer Out (GB)*</span><span class="sxs-lookup"><span data-stu-id="58864-172">*Data Transfer In (GB)*, *Data Transfer Out (GB)*</span></span> |
| <span data-ttu-id="58864-173">Region</span><span class="sxs-lookup"><span data-stu-id="58864-173">Region</span></span> | <span data-ttu-id="58864-174">The region to which the usage applies.</span><span class="sxs-lookup"><span data-stu-id="58864-174">The region to which the usage applies.</span></span> <span data-ttu-id="58864-175">Primarily used to assign rates to data transfers, because rates vary by region.</span><span class="sxs-lookup"><span data-stu-id="58864-175">Primarily used to assign rates to data transfers, because rates vary by region.</span></span> | <span data-ttu-id="58864-176">*Asia Pacific*, *Europe*, *Latin America*, *North America*</span><span class="sxs-lookup"><span data-stu-id="58864-176">*Asia Pacific*, *Europe*, *Latin America*, *North America*</span></span> |
| <span data-ttu-id="58864-177">SKU</span><span class="sxs-lookup"><span data-stu-id="58864-177">SKU</span></span> | <span data-ttu-id="58864-178">Unique Microsoft identifier for an offer.</span><span class="sxs-lookup"><span data-stu-id="58864-178">Unique Microsoft identifier for an offer.</span></span> | <span data-ttu-id="58864-179">*7UD-00001*</span><span class="sxs-lookup"><span data-stu-id="58864-179">*7UD-00001*</span></span> |
| <span data-ttu-id="58864-180">DetailLineItemId</span><span class="sxs-lookup"><span data-stu-id="58864-180">DetailLineItemId</span></span> | <span data-ttu-id="58864-181">An identifier and quantity to itemize different rates for a service or resource in a given billing period.</span><span class="sxs-lookup"><span data-stu-id="58864-181">An identifier and quantity to itemize different rates for a service or resource in a given billing period.</span></span> <span data-ttu-id="58864-182">For Azure tiered pricing, there may be one rate for up to a certain quantity of billable units, then a different rate after that quantity.</span><span class="sxs-lookup"><span data-stu-id="58864-182">For Azure tiered pricing, there may be one rate for up to a certain quantity of billable units, then a different rate after that quantity.</span></span> | <span data-ttu-id="58864-183">*1*</span><span class="sxs-lookup"><span data-stu-id="58864-183">*1*</span></span> |
| <span data-ttu-id="58864-184">ConsumedQuantity</span><span class="sxs-lookup"><span data-stu-id="58864-184">ConsumedQuantity</span></span> | <span data-ttu-id="58864-185">The amount of service consumed (such as hours or GB) during the reporting period.</span><span class="sxs-lookup"><span data-stu-id="58864-185">The amount of service consumed (such as hours or GB) during the reporting period.</span></span> <span data-ttu-id="58864-186">Enthält außerdem jede nicht berechnete Nutzung aus dem vorherigen Berichtszeitraum.</span><span class="sxs-lookup"><span data-stu-id="58864-186">Also includes any unbilled usage from previous reporting periods.</span></span> | <span data-ttu-id="58864-187">*11*</span><span class="sxs-lookup"><span data-stu-id="58864-187">*11*</span></span> |
| <span data-ttu-id="58864-188">IncludedQuantity</span><span class="sxs-lookup"><span data-stu-id="58864-188">IncludedQuantity</span></span> | <span data-ttu-id="58864-189">Enthaltene Einheiten als Teil des Angebots.</span><span class="sxs-lookup"><span data-stu-id="58864-189">Units included as part of the offer.</span></span> <span data-ttu-id="58864-190">Typically not present in CSP.</span><span class="sxs-lookup"><span data-stu-id="58864-190">Typically not present in CSP.</span></span> | <span data-ttu-id="58864-191">*0*</span><span class="sxs-lookup"><span data-stu-id="58864-191">*0*</span></span> |
| <span data-ttu-id="58864-192">OverageQuantity</span><span class="sxs-lookup"><span data-stu-id="58864-192">OverageQuantity</span></span> | <span data-ttu-id="58864-193">Units not included as part of the offer.</span><span class="sxs-lookup"><span data-stu-id="58864-193">Units not included as part of the offer.</span></span> <span data-ttu-id="58864-194">These must be paid for by the partner.</span><span class="sxs-lookup"><span data-stu-id="58864-194">These must be paid for by the partner.</span></span> <span data-ttu-id="58864-195">Equal to **ConsumedQuantity** minus **IncludedQuantity**.</span><span class="sxs-lookup"><span data-stu-id="58864-195">Equal to **ConsumedQuantity** minus **IncludedQuantity**.</span></span> | <span data-ttu-id="58864-196">*11*</span><span class="sxs-lookup"><span data-stu-id="58864-196">*11*</span></span> |
| <span data-ttu-id="58864-197">ListPrice</span><span class="sxs-lookup"><span data-stu-id="58864-197">ListPrice</span></span> | <span data-ttu-id="58864-198">Offer price in effect at subscription's start date.</span><span class="sxs-lookup"><span data-stu-id="58864-198">Offer price in effect at subscription's start date.</span></span> | <span data-ttu-id="58864-199">*$0.0808*</span><span class="sxs-lookup"><span data-stu-id="58864-199">*$0.0808*</span></span> |
| <span data-ttu-id="58864-200">PretaxCharges</span><span class="sxs-lookup"><span data-stu-id="58864-200">PretaxCharges</span></span> | <span data-ttu-id="58864-201">Equal to **ListPrist** multiplied by **OverageQuantity**, rounded to the nearest cent.</span><span class="sxs-lookup"><span data-stu-id="58864-201">Equal to **ListPrist** multiplied by **OverageQuantity**, rounded to the nearest cent.</span></span> | <span data-ttu-id="58864-202">*$0.085*</span><span class="sxs-lookup"><span data-stu-id="58864-202">*$0.085*</span></span> |
| <span data-ttu-id="58864-203">TaxAmount</span><span class="sxs-lookup"><span data-stu-id="58864-203">TaxAmount</span></span> | <span data-ttu-id="58864-204">Tax amount charged.</span><span class="sxs-lookup"><span data-stu-id="58864-204">Tax amount charged.</span></span> <span data-ttu-id="58864-205">Based on your market's tax rules and specific circumstances.</span><span class="sxs-lookup"><span data-stu-id="58864-205">Based on your market's tax rules and specific circumstances.</span></span> | <span data-ttu-id="58864-206">*$0.08*</span><span class="sxs-lookup"><span data-stu-id="58864-206">*$0.08*</span></span> |
| <span data-ttu-id="58864-207">PostTaxTotal</span><span class="sxs-lookup"><span data-stu-id="58864-207">PostTaxTotal</span></span> | <span data-ttu-id="58864-208">Gesamtbetrag nach Steuern, wo Steuern berechnet werden.</span><span class="sxs-lookup"><span data-stu-id="58864-208">Total after tax, when tax is applicable.</span></span> | <span data-ttu-id="58864-209">*$0.93*</span><span class="sxs-lookup"><span data-stu-id="58864-209">*$0.93*</span></span> |
| <span data-ttu-id="58864-210">Währung</span><span class="sxs-lookup"><span data-stu-id="58864-210">Currency</span></span> | <span data-ttu-id="58864-211">Währungstyp</span><span class="sxs-lookup"><span data-stu-id="58864-211">Currency type.</span></span> <span data-ttu-id="58864-212">Jede Abrechnungsentität verfügt nur über eine Währung.</span><span class="sxs-lookup"><span data-stu-id="58864-212">Each billing entity has only one currency.</span></span> <span data-ttu-id="58864-213">Check that it matches your first invoice and then after any major billing platform updates.</span><span class="sxs-lookup"><span data-stu-id="58864-213">Check that it matches your first invoice and then after any major billing platform updates.</span></span> | <span data-ttu-id="58864-214">*EUR*</span><span class="sxs-lookup"><span data-stu-id="58864-214">*EUR*</span></span> |
| <span data-ttu-id="58864-215">PretaxEffectiveRate</span><span class="sxs-lookup"><span data-stu-id="58864-215">PretaxEffectiveRate</span></span> | <span data-ttu-id="58864-216">Nettopreis pro Einheit.</span><span class="sxs-lookup"><span data-stu-id="58864-216">Pretax price per unit.</span></span> <span data-ttu-id="58864-217">Equal to **PretaxCharges** divided by **OverageQuantity**, rounded to the nearest cent.</span><span class="sxs-lookup"><span data-stu-id="58864-217">Equal to **PretaxCharges** divided by **OverageQuantity**, rounded to the nearest cent.</span></span> | <span data-ttu-id="58864-218">*$0.08*</span><span class="sxs-lookup"><span data-stu-id="58864-218">*$0.08*</span></span> |
| <span data-ttu-id="58864-219">PostTaxEffectiveRate</span><span class="sxs-lookup"><span data-stu-id="58864-219">PostTaxEffectiveRate</span></span> | <span data-ttu-id="58864-220">Bruttopreis pro Einheit.</span><span class="sxs-lookup"><span data-stu-id="58864-220">Post tax price per unit.</span></span> <span data-ttu-id="58864-221">Equal to **PostTaxTotal** divided by **OverageQuantity**, rounded to the nearest cent.</span><span class="sxs-lookup"><span data-stu-id="58864-221">Equal to **PostTaxTotal** divided by **OverageQuantity**, rounded to the nearest cent.</span></span> <span data-ttu-id="58864-222">Or, equal to **PretaxEffectiveRate** plus thet tax rate per unit amoun, rounded to the nearest cent.</span><span class="sxs-lookup"><span data-stu-id="58864-222">Or, equal to **PretaxEffectiveRate** plus thet tax rate per unit amoun, rounded to the nearest cent.</span></span> | <span data-ttu-id="58864-223">*$0.08*</span><span class="sxs-lookup"><span data-stu-id="58864-223">*$0.08*</span></span> |
| <span data-ttu-id="58864-224">ChargeType</span><span class="sxs-lookup"><span data-stu-id="58864-224">ChargeType</span></span> | <span data-ttu-id="58864-225">The [type of charge](recon-file-charge-types.md) or adjustment.</span><span class="sxs-lookup"><span data-stu-id="58864-225">The [type of charge](recon-file-charge-types.md) or adjustment.</span></span> | <span data-ttu-id="58864-226">See [charge types](recon-file-charge-types.md).</span><span class="sxs-lookup"><span data-stu-id="58864-226">See [charge types](recon-file-charge-types.md).</span></span> |
| <span data-ttu-id="58864-227">CustomerBillableAccount</span><span class="sxs-lookup"><span data-stu-id="58864-227">CustomerBillableAccount</span></span> | <span data-ttu-id="58864-228">Unique account identifier in the Microsoft billing platform.</span><span class="sxs-lookup"><span data-stu-id="58864-228">Unique account identifier in the Microsoft billing platform.</span></span> | <span data-ttu-id="58864-229">*1280018095*</span><span class="sxs-lookup"><span data-stu-id="58864-229">*1280018095*</span></span> |
| <span data-ttu-id="58864-230">UsageDate</span><span class="sxs-lookup"><span data-stu-id="58864-230">UsageDate</span></span> | <span data-ttu-id="58864-231">Datum der Service-Bereitstellung.</span><span class="sxs-lookup"><span data-stu-id="58864-231">Date of service deployment.</span></span> | <span data-ttu-id="58864-232">*2/1/2019 0:00*</span><span class="sxs-lookup"><span data-stu-id="58864-232">*2/1/2019 0:00*</span></span> |
| <span data-ttu-id="58864-233">MeteredRegion</span><span class="sxs-lookup"><span data-stu-id="58864-233">MeteredRegion</span></span> | <span data-ttu-id="58864-234">Identifies the location of a data center within the region (for services where this value is applicable and populated).</span><span class="sxs-lookup"><span data-stu-id="58864-234">Identifies the location of a data center within the region (for services where this value is applicable and populated).</span></span> | <span data-ttu-id="58864-235">*East Asia*, *South East Asia*, *North Europe*, *West Europe*, *North Central US*, *South Central US*</span><span class="sxs-lookup"><span data-stu-id="58864-235">*East Asia*, *South East Asia*, *North Europe*, *West Europe*, *North Central US*, *South Central US*</span></span> |
| <span data-ttu-id="58864-236">MeteredService</span><span class="sxs-lookup"><span data-stu-id="58864-236">MeteredService</span></span> | <span data-ttu-id="58864-237">Identifies the individual Azure service usage when it's not specifically identified in the **ServiceName** column.</span><span class="sxs-lookup"><span data-stu-id="58864-237">Identifies the individual Azure service usage when it's not specifically identified in the **ServiceName** column.</span></span> <span data-ttu-id="58864-238">For example, data transfers are reported as *Microsoft Azure - All Services* in the **ServiceName** column.</span><span class="sxs-lookup"><span data-stu-id="58864-238">For example, data transfers are reported as *Microsoft Azure - All Services* in the **ServiceName** column.</span></span> | <span data-ttu-id="58864-239">*AccessControl*, *CDN*, *Compute*, *Database*, *ServiceBus*, *Storage*</span><span class="sxs-lookup"><span data-stu-id="58864-239">*AccessControl*, *CDN*, *Compute*, *Database*, *ServiceBus*, *Storage*</span></span> |
| <span data-ttu-id="58864-240">MeteredServiceType</span><span class="sxs-lookup"><span data-stu-id="58864-240">MeteredServiceType</span></span> | <span data-ttu-id="58864-241">Subheading for **MeteredService** field that provides additional clarification of Azure service usage.</span><span class="sxs-lookup"><span data-stu-id="58864-241">Subheading for **MeteredService** field that provides additional clarification of Azure service usage.</span></span> | <span data-ttu-id="58864-242">*EXTERNAL*</span><span class="sxs-lookup"><span data-stu-id="58864-242">*EXTERNAL*</span></span> |
| <span data-ttu-id="58864-243">Projizieren</span><span class="sxs-lookup"><span data-stu-id="58864-243">Project</span></span> | <span data-ttu-id="58864-244">Customer-defined name for their service instance.</span><span class="sxs-lookup"><span data-stu-id="58864-244">Customer-defined name for their service instance.</span></span> | <span data-ttu-id="58864-245">*ORDDC52E52FDEF405786F0642DD0108BE4*</span><span class="sxs-lookup"><span data-stu-id="58864-245">*ORDDC52E52FDEF405786F0642DD0108BE4*</span></span> |
| <span data-ttu-id="58864-246">ServiceInfo</span><span class="sxs-lookup"><span data-stu-id="58864-246">ServiceInfo</span></span> | <span data-ttu-id="58864-247">The number of Azure Service Bus connections that were provisioned and utilized on a given day.</span><span class="sxs-lookup"><span data-stu-id="58864-247">The number of Azure Service Bus connections that were provisioned and utilized on a given day.</span></span> | <span data-ttu-id="58864-248">*1.000000 Connections / 30 days* (if you had an individually provisioned connection during a 30-day month), *25 Connections / 30 Days – Used: 1.000000* (if you had a 25 pack of Service Bus connections provisioned and you utilized 1 during that day)</span><span class="sxs-lookup"><span data-stu-id="58864-248">*1.000000 Connections / 30 days* (if you had an individually provisioned connection during a 30-day month), *25 Connections / 30 Days – Used: 1.000000* (if you had a 25 pack of Service Bus connections provisioned and you utilized 1 during that day)</span></span> |
| <span data-ttu-id="58864-249">Kunden-ID</span><span class="sxs-lookup"><span data-stu-id="58864-249">CustomerID</span></span> | <span data-ttu-id="58864-250">Unique Microsoft identifier for the customer, in GUID format.</span><span class="sxs-lookup"><span data-stu-id="58864-250">Unique Microsoft identifier for the customer, in GUID format.</span></span> | <span data-ttu-id="58864-251">*ORDDC52E52FDEF405786F0642DD0108BE4*</span><span class="sxs-lookup"><span data-stu-id="58864-251">*ORDDC52E52FDEF405786F0642DD0108BE4*</span></span> |
| <span data-ttu-id="58864-252">DomainName</span><span class="sxs-lookup"><span data-stu-id="58864-252">DomainName</span></span> | <span data-ttu-id="58864-253">Customer's domain name.</span><span class="sxs-lookup"><span data-stu-id="58864-253">Customer's domain name.</span></span> <span data-ttu-id="58864-254">Dieses Feld wird ggf. bis zum zweiten Abrechnungszyklus leer angezeigt.</span><span class="sxs-lookup"><span data-stu-id="58864-254">This field may appear blank until the second billing cycle.</span></span> | <span data-ttu-id="58864-255">*example.onmicrosoft.com*</span><span class="sxs-lookup"><span data-stu-id="58864-255">*example.onmicrosoft.com*</span></span> |
| <span data-ttu-id="58864-256">Einheit</span><span class="sxs-lookup"><span data-stu-id="58864-256">Unit</span></span> | <span data-ttu-id="58864-257">The unit of the resource **Name**.</span><span class="sxs-lookup"><span data-stu-id="58864-257">The unit of the resource **Name**.</span></span> | <span data-ttu-id="58864-258">*GB* or *HOURS*</span><span class="sxs-lookup"><span data-stu-id="58864-258">*GB* or *HOURS*</span></span> |