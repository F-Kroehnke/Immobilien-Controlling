# Immobilien-Controlling – Power BI Projekt

## 1. Einführung

Dieses Projekt umfasst ein Power BI Cockpit zur finanziellen Steuerung eines Immobilienportfolios. Es konsolidiert Einnahmen, Ausgaben, Mietverträge und Wohnungsdaten zu einem einheitlichen Reporting.

Ziel ist es, eine klare Übersicht über ein Immobilienportfolio in nur ein paar Minuten zu erhalten.
-Einnahmen und Ausgaben (gesamt und je Wohnung)
-Betriebsergebnis (gesamt und je Wohnung)
-Kategorieanalyse (welche Kostenkategorien steigen, welche sinken?)
-Wohnungsanalyse II (wie performt welche Wohnung)
Einnahmen, Ausgaben und das wirtschaftliche Ergebnis je Wohnung, Kategorie und Zeitraum nachvollziehbar darzustellen sowie Abweichungen zwischen Soll- und Ist-Mieten transparent zu machen.

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

![Seite2](https://github.com/F-Kroehnke/Test/blob/89b313cd7e79611e536ef34946757fa1e736390a/Bilder/Seite%202%2C%20Wohnungsanalyse.png)

**Kostenanalyse**
Diese Seite gliedert die Ausgaben nach Kategorien und macht die wesentlichen Kostentreiber sowie deren Entwicklung über die Zeit sichtbar. Sie unterstützt die gezielte Identifikation von Einsparpotenzialen.

![Seite3](https://github.com/F-Kroehnke/Test/blob/89b313cd7e79611e536ef34946757fa1e736390a/Bilder/Seite%203%2C%20Kostenanalyse.png)

**Mieteinnahmenübersicht**
Im Mittelpunkt steht der Vergleich von Soll- und Ist-Miete sowie der Zahlungsstatus je Wohnung und Monat. Die Seite macht Mietausfälle und Überzahlungen sichtbar und unterstützt das Forderungsmanagement.

![Seite4](https://github.com/F-Kroehnke/Test/blob/89b313cd7e79611e536ef34946757fa1e736390a/Bilder/Seite%204%2C%20Mieteinnahmen%C3%BCbersicht.png)

**Wohnungsanalyse II**
Diese Seite ergänzt die Wohnungsanalyse um die Transaktionsebene und zeigt Einzelbuchungen je Objekt im Zeitverlauf. Sie ermöglicht eine detaillierte Nachvollziehbarkeit der Ergebnisentwicklung pro Wohnung.

![Seite5](https://github.com/F-Kroehnke/Test/blob/89b313cd7e79611e536ef34946757fa1e736390a/Bilder/Seite%205%2C%20Wohnungsanalyse%20II.png)

**Kategorieanalyse**
Hier werden Ausgaben über mehrere Jahre und Wohnungen hinweg nach Kategorie und Typ analysiert. Die Seite liefert eine detaillierte Kostenübersicht inklusive durchschnittlicher Ausgaben pro Wohnung und Monat.

![Seite5](https://github.com/F-Kroehnke/Test/blob/89b313cd7e79611e536ef34946757fa1e736390a/Bilder/Seite%206%2C%20Wohnungsanalyse%20II.png)

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

![Seite1](https://github.com/F-Kroehnke/Test/blob/b4dc81aa3d9da574308acd3e2940506ce7f06f4e/Bilder/Datenmodell.png)

Die zentralen Faktentabellen sind **Fact_Transaktionen** (Einzelbuchungen mit Betrag, Datum, Kategorie und Wohnungszuordnung) und **Fact_Mietkonditionen** (vertragliche Soll-Mieten und Nebenkosten je Mietvertrag und Gültigkeitszeitraum).

Diesen sind folgende Dimensionstabellen zugeordnet: **Dim_Wohnung** (Objektstammdaten), **Dim_Kategorie** (Klassifizierung von Einnahmen und Ausgaben), **Dim_Datum** (Zeitintelligenz), **Dim_Mieter** (Mieterstammdaten) und **Dim_Mietvertrag** (Vertragsinformationen, verknüpft mit Wohnung und Mieter).

Ergänzend existieren themenbezogene Tabellen ohne eigene Datenspalten (Finanzübersicht, Portfolioübersicht, Ausgaben, Einnahmen, Parameter), in denen die DAX-Measures für Reporting-Zwecke organisiert sind. Die Beziehungen zwischen den Tabellen sind als 1:n-Verknüpfungen von den Dimensionen zu den Faktentabellen modelliert.

## 6. Abschluss

Dieses Projekt zeigt, wie ein vollständiges Immobilien-Controlling-Cockpit mit Power BI aufgebaut wird – von der Datenmodellierung über die Berechnung betriebswirtschaftlicher Kennzahlen bis zur verständlichen Visualisierung der Ergebnisse.

Im Mittelpunkt steht der Business Value: Eine konsolidierte, jederzeit abrufbare Entscheidungsgrundlage für die Steuerung eines Immobilienportfolios, die Transparenz über Ertragslage, Kostenstruktur und Mietzahlungen schafft.

## 7. Hinweis zum Projekt

Die in diesem Dashboard dargestellten Daten sind vollständig **synthetisch** und wurden ausschließlich zu Demonstrations- und Portfoliozwecken erstellt.

Es werden **keine realen Personen-, Wohnungs- oder Kundendaten** verarbeitet, gespeichert oder dargestellt. Sämtliche Inhalte, Datensätze und Visualisierungen dienen ausschließlich der Veranschaulichung technischer und analytischer Funktionen.

Ein Bezug zu tatsächlich existierenden Personen, Immobilien oder Unternehmen ist weder beabsichtigt noch gegeben.


