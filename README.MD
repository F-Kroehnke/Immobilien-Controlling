# Immobilien-Controlling Cockpit – Power BI Projekt

## 1. Einführung

Dieses Projekt umfasst ein Power BI Cockpit zur finanziellen Steuerung eines Immobilienportfolios. Es konsolidiert Mieteinnahmen, Ausgaben, Mietverträge und Transaktionsdaten aus mehreren Wohnungen zu einem einheitlichen Reporting.

Ziel ist es, Einnahmen, Ausgaben und das wirtschaftliche Ergebnis je Wohnung, Kategorie und Zeitraum nachvollziehbar darzustellen sowie Abweichungen zwischen Soll- und Ist-Mieten transparent zu machen.

Dadurch wird eine fundierte Entscheidungsgrundlage für die Steuerung des Portfolios geschaffen: Kostentreiber, Mietausfälle und Ertragsunterschiede zwischen einzelnen Objekten lassen sich frühzeitig erkennen und bewerten.

## 2. Dashboard Übersicht

Das Dashboard bietet eine konsolidierte Sicht auf alle finanzrelevanten Kennzahlen eines Immobilienportfolios – von der Gesamtperformance bis zur Analyse einzelner Wohnungen und Kostenkategorien. Es verbindet Zeitreihenanalysen, Objektvergleiche und Detailtransaktionen in einem zusammenhängenden Reporting.

Es eignet sich für private Vermieter, Immobilienverwalter und Property Manager, die einen wiederkehrenden Überblick über die wirtschaftliche Entwicklung ihres Bestands benötigen.

Der Mehrwert liegt in der Zusammenführung verteilter Einzeldaten (Mietverträge, Transaktionen, Kosten) zu einem durchgängigen Controlling-Instrument, das Trends, Abweichungen und Handlungsbedarf sichtbar macht, ohne dass manuelle Auswertungen erforderlich sind.

## 3. Dashboard Seiten

**Finanzübersicht**
Diese Seite zeigt die wirtschaftliche Gesamtsituation des Portfolios: Einnahmen, Ausgaben und das daraus resultierende Ergebnis im Zeitverlauf sowie kumuliert über die Jahre. Sie dient als Einstiegspunkt, um die finanzielle Entwicklung auf einen Blick zu erfassen.

![Seite1](https://github.com/F-Kroehnke/Test/blob/c28355b1338ece708955e7af6df63ba0d015a58a/Bilder/Seite%201%2C%20Dashboard.png)

**Wohnungsanalyse**
Hier wird die Wirtschaftlichkeit der einzelnen Wohnungen verglichen, einschließlich ihres Anteils am Gesamtergebnis und der Veränderung gegenüber dem Vorjahr. Die Seite zeigt, welche Objekte überdurchschnittlich performen und wo Optimierungsbedarf besteht.

![Seite2](https://github.com/F-Kroehnke/Test/blob/main/Bilder/Seite%202%2C%20Wohnungsanalyse.png)

**Kostenanalyse**
Diese Seite gliedert die Ausgaben nach Kategorien und macht die wesentlichen Kostentreiber sowie deren Entwicklung über die Zeit sichtbar. Sie unterstützt die gezielte Identifikation von Einsparpotenzialen.

**Mieteinnahmenübersicht**
Im Mittelpunkt steht der Vergleich von Soll- und Ist-Miete sowie der Zahlungsstatus je Wohnung und Monat. Die Seite macht Mietausfälle und Überzahlungen sichtbar und unterstützt das Forderungsmanagement.

![Seite1](https://github.com/F-Kroehnke/Test/blob/c28355b1338ece708955e7af6df63ba0d015a58a/Bilder/Seite%201%2C%20Dashboard.png)

**Wohnungsanalyse II**
Diese Seite ergänzt die Wohnungsanalyse um die Transaktionsebene und zeigt Einzelbuchungen je Objekt im Zeitverlauf. Sie ermöglicht eine detaillierte Nachvollziehbarkeit der Ergebnisentwicklung pro Wohnung.

![Seite1](https://github.com/F-Kroehnke/Test/blob/c28355b1338ece708955e7af6df63ba0d015a58a/Bilder/Seite%201%2C%20Dashboard.png)

**Kategorieanalyse**
Hier werden Ausgaben über mehrere Jahre und Wohnungen hinweg nach Kategorie und Typ analysiert. Die Seite liefert eine detaillierte Kostenübersicht inklusive durchschnittlicher Ausgaben pro Wohnung und Monat.

![Seite1](https://github.com/F-Kroehnke/Test/blob/c28355b1338ece708955e7af6df63ba0d015a58a/Bilder/Seite%201%2C%20Dashboard.png)

## 4. Skills Showcase

- Power BI (DAX, Power Query)
- Datenmodellierung (Star-Schema-Design)
- Data Cleaning und Datenaufbereitung
- Data Visualization
- Business Analysis im Immobilienkontext
- KPI-Definition (Ergebnis, YoY-Veränderung, Ist-/Soll-Vergleich, Anteilskennzahlen)
- Strukturierung von Measures in themenbezogenen Tabellen (Finanz-, Portfolio- und Ausgabenkennzahlen)
- Berücksichtigung datenschutzrelevanter Aspekte bei personenbezogenen Daten (DSGVO)

## 5. Datenmodell

Das Datenmodell folgt einem Star-Schema und trennt Fakten- von Dimensionsdaten.

![Seite1](https://github.com/F-Kroehnke/Test/blob/c28355b1338ece708955e7af6df63ba0d015a58a/Bilder/Seite%201%2C%20Dashboard.png)

Die zentralen Faktentabellen sind **Fact_Transaktionen** (Einzelbuchungen mit Betrag, Datum, Kategorie und Wohnungszuordnung) und **Fact_Mietkonditionen** (vertragliche Soll-Mieten und Nebenkosten je Mietvertrag und Gültigkeitszeitraum).

Diesen sind folgende Dimensionstabellen zugeordnet: **Dim_Wohnung** (Objektstammdaten), **Dim_Kategorie** (Klassifizierung von Einnahmen und Ausgaben), **Dim_Datum** (Zeitintelligenz), **Dim_Mieter** (Mieterstammdaten) und **Dim_Mietvertrag** (Vertragsinformationen, verknüpft mit Wohnung und Mieter).

Ergänzend existieren themenbezogene Tabellen ohne eigene Datenspalten (Finanzübersicht, Portfolioübersicht, Ausgaben, Einnahmen, Parameter), in denen die DAX-Measures für Reporting-Zwecke organisiert sind. Die Beziehungen zwischen den Tabellen sind als 1:n-Verknüpfungen von den Dimensionen zu den Faktentabellen modelliert.

## 6. Abschluss

Dieses Projekt zeigt, wie ein vollständiges Immobilien-Controlling-Cockpit mit Power BI aufgebaut wird – von der Datenmodellierung über die Berechnung betriebswirtschaftlicher Kennzahlen bis zur verständlichen Visualisierung der Ergebnisse.

Im Mittelpunkt steht der Business Value: Eine konsolidierte, jederzeit abrufbare Entscheidungsgrundlage für die Steuerung eines Immobilienportfolios, die Transparenz über Ertragslage, Kostenstruktur und Mietzahlungen schafft.

