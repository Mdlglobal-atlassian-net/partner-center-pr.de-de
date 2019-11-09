---
title: Azure-Plan-Preisliste | Partner Center
ms.topic: article
ms.date: 11/01/2019
description: Anzeigen der Preisliste für Abonnements im Rahmen eines Azure-Plans
author: LauraBrenner
ms.author: labrenne
Keywords: ''
robots: ''
ms.localizationpriority: high
ms.openlocfilehash: 53e5327b505de1c1860e44b477aca21b5aef2d2b
ms.sourcegitcommit: 646536a113584f1572de851e22a212a6f77e64d7
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 11/01/2019
ms.locfileid: "73428551"
---
# <a name="price-list-for-the-new-commerce-experience-in-csp-for-azure"></a>Preisliste für die neue E-Commerce-Benutzeroberfläche in CSP für Azure 

Die Preisliste für die neue Azure E-Commerce-Benutzeroberfläche in CSP ist im Partner Center veröffentlicht. Die Preisliste wird dynamisch in einer exakten Echtzeitdatei bereitgestellt, und die Preise werden nur in USD angezeigt. Die Abrechnung erfolgt jedoch in der unterstützten Währung, die am Währungsstandort des Kunden gilt. Weitere Informationen zur Abrechnung am Währungsstandort des Kunden finden Sie unter [Azure-Plan: Abrechnung](azure-plan-billing.md).

## <a name="see-pricing-for-subscriptions-under-the-azure-plan-pricing"></a>Anzeigen der Preisliste für Abonnements im Rahmen eines Azure-Plans

1. Wählen Sie im Menü des Partner Centers auf der linken Seite **Verkaufen** und dann **Marketplace** aus.

2. Wählen Sie neben **Exporttyp** **Preise für Azure-Plannutzung** aus.

3. Wählen Sie neben **Preise für Datum** das gewünschte Datum aus, beispielsweise **Aktuell**. Hinweis: Sie können auch **Wechselkurse** auswählen, um die aktuellen Wechselkurse zu exportieren.

![Azure-Preise 2](images/azure/pricelist2.jpg)

4. Wählen Sie unter **Marketplace** den **Typ** und die **Kategorie** des Produkts aus, oder suchen Sie nach einem Produkt. Auf der Grundlage Ihrer Suche werden die verfügbaren Produkte angezeigt.

![pricing](images/azure/Azurepricelist1.jpg)

5. Wählen Sie dann **Preisliste für Azure-Plan exportieren** aus, um für die von Ihnen ausgewählten Produkte die Preise im Azure-Plan herunterzuladen.


![Preisliste exportieren](images/azure/pricelist1.png)



## <a name="azure-price-list-specifics"></a>Besonderheiten der Azure-Preisliste

- Die Preise für Azure-Pläne sind auf der Marketplace-Seite im Partner Center unter **Verkaufen** verfügbar.

- Exporte sind für die Azure-Plan-Verbrauchsdienste, Azure-Reservierungen und Wechselkurse verfügbar.

- Zu den Exportoptionen gehören:

    - **Preise heute**: Dies schließt alle Verbrauchseinheiten und Preise vom 1. des Monats bis zum aktuellen Datum des aktuellen Monats ein. Dies schließt neue Preise, geänderte Preise oder entfernte Preise ein. Alle Preise sind mit den Start- und Enddaten ihrer Gültigkeit aufgelistet, um zu erläutern, ob sie neu sind oder entfernt wurden.

    - **Preise des Vormonats**: Die Downloads für jeden Ressourcentyp erfolgen monatsweise. Bei Preisdateien schließt dies alle Verbrauchseinheiten ein, die für den betreffenden Monat zum Zeitpunkt des Downloads verfügbar sind. Wenn in der Monatsmitte eine neue Verbrauchseinheit auftritt, wird sie als Verbrauchseinheit mit einem Gültigkeitsdatum aufgeführt, das ihre Verfügbarkeit angibt. Ähnliches gilt für eingestellte Preise, die mit dem Enddatum ihrer Gültigkeit aufgeführt werden, das angibt, ab wann sie nicht mehr verfügbar sind.

    - **Wechselkurse**: Wechselkurse stehen für den Download am Tag vor dem 1. des Monats um 18:00 Uhr PST zur Verfügung. Wenn Sie beispielsweise die Wechselkurse für November erfahren möchten, laden Sie die Wechselkurse am 31. Oktober herunter. Die Wechselkurse des Vormonats sind ebenfalls verfügbar.

- Die Preise in den Preislisten sind Direktpreise. Einige Partner sind möglicherweise für vom Partner erworbene Guthaben qualifiziert. Informationen zur Berechnung des vom Partner erworbenen Guthabens finden Sie unter [Wie von Partnern erworbene Guthaben berechnet und bezahlt werden](partner-earned-credit-explanation.md).

- **Berechtigte Dienste**: Das vom Partnern erworbene Guthaben kann auf Dienste angerechnet werden, die in den **Preisen für Azure-Plannutzung** aufgelistet sind, die Partner von der Seite [Azure-Plan-Preise](https://partner.microsoft.com/commerce/sales) exportieren können. Beachten Sie, dass es Ausnahmen gibt, beispielsweise Produkte von Drittanbietern, die in der Tags-Spalte der Preisliste für die Azure-Plannutzung und Azure-Plan Reservierungen als „Drittanbieter“ gekennzeichnet sind.

## <a name="price-list-data"></a>Preislistendaten

|**Feld**   |**Beschreibung**   |
|--------------------------|:---------------------------|
|ProductTitle  |Der Titel oder Name des Produkts|
|ProductID   |Die ID des Produkts|
|SKuId|Die ID der SKU|
|SkuTitle|Der Titel oder Name der SKU|
|Verleger|Der Originalanbieter ist immer Microsoft|
|SkuDescription|Beschreibung der SKU|
|UnitOfMeasure|Die Einheiten die in Rechnung gestellt oder abgerechnet werden|
|TermDuration|Bei Produkten mit Laufzeit die Länge der Laufzeit, auf Reservierungen anwendbar|
|Markt|Der Markt, für den diese Preise gelten|
|Währung|Die Währung für die Preise|
|UnitPrice|Preis pro Einheit|
|PricingTierRangeMin|Bei mehrstufigen Preisen gilt der Mindestpreis|
|PricingTierRangeMax|Bei mehrstufigen Preisen gilt der Höchstpreis|
|EffectiveStartDate|Startdatum der Preise|
|EffectiveEndDate|Enddatum der Preise|
|MeterIds|Die Verbrauchseinheit-ID der Produkt-SKU|
|MeterType|Typ der Verbrauchseinheit|
|Tags|Eigenschaften des Artikels, bei Azure-Plan-Preisen ist die Azure oder Azure und Reservierungen (speziell für Reservierungen)|

Ausführliche [Preislisteninformationen](https://partner.microsoft.com/commerce/sales?type=Any&category=Any)  