# Immobilien-Controlling – Power BI Projekt

## 1. Einführung

Dieses Projekt umfasst ein **Power BI Cockpit** zur finanziellen Steuerung eines **Immobilienportfolios**.

Ziel ist es, eine schnelle und transparente Übersicht über die **wirtschaftliche Entwicklung eines Immobilienportfolios** zu ermöglichen. Der Bericht umfasst folgende Analysebereiche:

- **Portfolioübersicht** - Einnahmen, Ausgaben und Betriebsergebnis
- **Wohnungsanalyse** - Performancevergleich einzelner Wohnungen
- **Kostenanalyse** - Entwicklung und Vergleich verschiedener Kostenkategorien
- **Mieteinnahmenübersicht** - Soll-Ist-Mietvergleich und Analyse von Mietabweichungen
- **Wohnungsdetailanalyse** - Entwicklung des Betriebsergebnisses und Ursachenanalyse einzelner Wohnungen
- **Kategoriedetailanalyse** - Detaillierte Untersuchung der Kostenentwicklung einzelner Kategorien

Dadurch wird eine fundierte Entscheidungsgrundlage für die Steuerung eines Immobilienportfolios geschaffen.

![Seite1](https://github.com/F-Kroehnke/Test/blob/main/Bilder/Seite%201%2C%20Portfolio%C3%BCbersicht.png)

*(Screenshot für erste Berichtsseite "Portfolioübersicht". Erläuterung der Berichtsseite unter 3.)*

## 2. Dashboard Übersicht

Das Dashboard bietet eine **zentrale Übersicht** über die finanzielle Performance eines Immobilienportfolios, von Gesamtkennzahlen bis zur Analyse einzelner Wohnungen und Kostenkategorien. Es verbindet Zeitreihen, Objektvergleiche und Detailtransaktionen in einem einheitlichen Reporting.

Alle Ansichten können über gemeinsame **Filter** nach Jahr und Wohnung eingegrenzt werden, um gezielte Analysen einzelner Objekte oder Zeiträume zu ermöglichen.

Durch die Konsolidierung von **Mietvertrags-, Transaktion-, Mieter und Wohnungsdaten** entsteht ein **automatisiertes** Controlling-Instrument, das Trends, Abweichungen und Optimierungspotenziale transparent macht.

## 3. Dashboard Seiten

**Portfolioübersicht**

*(Screenshot oben bereits gezeigt, kein zweites Bild nötig)*

Diese Seite bildet den **wirtschaftlichen Gesamtüberblick** des Portfolios ab.

- Wie hoch ist das aktuelle Gesamtergebnis des Portfolios?
- Wie haben sich Einnahmen und Ausgaben über die Zeit entwickelt?
- Wie verteilt sich das Ergebnis auf die einzelnen Wohnungen?
- Wie entwickelt sich das kumulative Ergebnis über die Jahre?

**Wohnungsanalyse**

Diese Seite vergleicht die **Wirtschaftlichkeit der einzelnen Objekte** untereinander.

![Seite2](https://github.com/F-Kroehnke/Immobilien-Controlling/blob/main/Bilder/Seite%202%2C%20Wohnungsanalyse.png)

- Welche Wohnung erzielt das beste Ergebnis?
- Wie hoch ist der Anteil jeder Wohnung am Gesamtergebnis?
- Wie hat sich das Ergebnis je Wohnung im Vergleich zum Vorjahr verändert?

**Kostenanalyse**

Diese Seite gliedert die **Ausgaben** nach Kategorien und macht die wesentlichen Kostentreiber sichtbar.

![Seite3](https://github.com/F-Kroehnke/Immobilien-Controlling/blob/996c621d3444955fe0bb3a2b9641e9b3645a42c1/Bilder/Seite%203%2C%20Kostenanalyse.png)

- Welche Kostenkategorien verursachen die höchsten Ausgaben?
- Wie hoch sind die durchschnittlichen Monatsausgaben je Kategorie?
- Wie haben sich die Ausgaben im Vergleich zum Vorjahr verändert?
- Wie ist der prozentuale Anteil der einzelnen Kategorien an den Gesamtausgaben?

**Mieteinnahmenübersicht**

Diese Seite stellt **Soll- und Ist-Mieten** gegenüber und macht den Zahlungsstatus je Wohnung transparent.

![Seite4](https://github.com/F-Kroehnke/Test/blob/main/Bilder/Seite%204%2C%20Mieteinnahmen%C3%BCbersicht.png)

- Wie hoch ist der Unterschied zwischen Soll- und Ist-Miete?
- Welche Wohnungen weisen Mietausfälle oder Überzahlungen auf?
- Wie ist der aktuelle Zahlungsstatus je Wohnung und Monat?
- Wie hoch sind die kumulierten Sollkosten im betrachteten Zeitraum?

**Wohnungsanalyse II**

Diese Seite ergänzt die Wohnungsanalyse um die **Transaktionsebene** und ermöglicht eine detaillierte Nachvollziehbarkeit der Ergebnisentwicklung je Objekt.

![Seite5](https://github.com/F-Kroehnke/Test/blob/main/Bilder/Seite%205%2C%20Wohnungsanalyse%20II.png)

- Welche Einzeltransaktionen liegen dem Ergebnis einer Wohnung zugrunde?
- Wie entwickeln sich Einnahmen und Ausgaben einer Wohnung im Monatsverlauf?
- Wie hoch ist das durchschnittliche monatliche Ergebnis je Wohnung?

**Kategorieanalyse**

Diese Seite analysiert die **Ausgaben auf Kategorieebene** über Wohnungen und Zeiträume hinweg.

![Seite6](https://github.com/F-Kroehnke/Test/blob/main/Bilder/Seite%206%2C%20Kategorieanalyse.png)

- Wie entwickeln sich die Ausgaben einer Kategorie über mehrere Jahre?
- Welche Wohnungen erzeugen in einer Kategorie die höchsten Kosten?
- Wie hoch sind die durchschnittlichen Ausgaben pro Wohnung und Monat?
- Welche Einzeltransaktionen stecken hinter den Kategorieausgaben?

## 4. Skills Showcase

Dieses Projekt demonstriert den praxisorientierten Einsatz folgender **Technologien und Fähigkeiten**:

- Power BI, Excel
- Datenmodellierung (Star-Schema-Design)
- Data Cleaning und Datenaufbereitung (Power Query)
- Data Visualization
- Business Analysis im Immobilienkontext
- Datumstabelle
- KPI-Erstellung DAX:
  - CALCULATE()
  - FILTER()
  - ALL()
  - SUMX()
  - DIVIDE()
  - DISTINCTCOUNT()
  - SAMEPERIODLASTYEAR()
- Berichtsdokumentation
- Tooltips (KPI Defintion)
- Strukturierung von Measures in themenbezogenen Tabellen (Finanz-, Portfolio- und Ausgabenkennzahlen)
- GitHub

## 5. Datenmodell

Das Datenmodell folgt einem **Star-Schema** und trennt **Fakten- von Dimensionsdaten**.

![Seite1](https://github.com/F-Kroehnke/Immobilien-Controlling/blob/main/Bilder/Datenmodell.png)

Die zentralen **Faktentabellen** sind 
- Fact_Transaktionen (Einzelbuchungen mit Betrag, Datum, Kategorie und Wohnungszuordnung) und
- Fact_Mietkonditionen (vertragliche Soll-Mieten und Nebenkosten je Mietvertrag und Gültigkeitszeitraum).

Diesen sind folgende **Dimensionstabellen** zugeordnet: 
- Dim_Wohnung (Objektstammdaten)
- Dim_Kategorie (Klassifizierung von Einnahmen und Ausgaben) 
- Dim_Datum (Zeitintelligenz)
- Dim_Mieter (Mieterstammdaten)
- Dim_Mietvertrag (Vertragsinformationen, verknüpft mit Wohnung und Mieter).

## 6. Abschluss

Dieses Projekt zeigt, wie ein vollständiges **Immobilien-Controlling-Cockpit mit Power BI** aufgebaut wird – von der Datenmodellierung über die Berechnung betriebswirtschaftlicher Kennzahlen bis zur verständlichen Visualisierung der Ergebnisse.

Im Mittelpunkt steht der **Business Value**: Eine konsolidierte, jederzeit abrufbare Entscheidungsgrundlage für die Steuerung eines Immobilienportfolios, die Transparenz über Ertragslage, Kostenstruktur und Mietzahlungen schafft.

## 7. Hinweis zum Projekt

Die in diesem Dashboard dargestellten Daten sind vollständig **synthetisch** und wurden ausschließlich zu Demonstrations- und Portfoliozwecken erstellt.

Es werden **keine realen Personen-, Wohnungs- oder Kundendaten** verarbeitet, gespeichert oder dargestellt. Sämtliche Inhalte, Datensätze und Visualisierungen dienen ausschließlich der Veranschaulichung technischer und analytischer Funktionen.

Ein Bezug zu tatsächlich existierenden Personen, Immobilien oder Unternehmen ist weder beabsichtigt noch gegeben.


