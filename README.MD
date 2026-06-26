# Einnahmen- und Ausgabenanalyse, Power-BI

## Einführung
 
 Dieses Projekt umfasst die **Entwicklung eines interaktiven Power-BI-Dashboards** zur **Analyse von Einnahmen, Ausgaben** und **Sparaktivitäten** auf Basis einer **strukturierten Excel-Datenquelle**. 
 
 Ziel ist es, finanzielle Daten transparent, nachvollziehbar und zeitorientiert auszuwerten.

Durch **automatisierte Datenverarbeitung**, **interaktive Filter** und **klar strukturierte Visualisierungen** wird eine **transparente Analyse der finanziellen Situation** ermöglicht und unterstützt **fundierte, datenbasierte Entscheidungen**.

## Dashboard Übersicht

Das **Einnahmen- und Ausgaben-Dashboard** bietet eine **umfassende, interaktive Finanzanalyse** in Power-BI. Mit **Jahres- und Monat-Slicern** sowie **Kategorien-Filtern** können Benutzer **individuelle Zeiträume** und **Bereiche** auswählen, um Einnahmen, Ausgaben und Sparaktivitäten gezielt zu überwachen.

Es eignet sich ideal für Privatanwender, Selbstständige und kleine Teams, die transparente, datenbasierte Entscheidungen treffen möchten. Das Dashboard liefert klare Visualisierungen, macht finanzielle Trends, Abweichungen und Potenziale auf einen Blick sichtbar und unterstützt so effektive Budgetplanung, Kostenkontrolle und strategische Spar- oder Investitionsentscheidungen.

### Seite 1: Dashboard

![Dashboard Seite 1](/Dashboard_Seite_1.png)

Die erste Seite des Dashboards bietet eine zeitbasierte Analyse der Finanzen mit **Jahres- und Monat-Slicern**, die alle Visuals entsprechend filtern.

- **Karte:** Zeigt das **Ergebnis** von **Einnahmen** und **Ausgaben**. Positive Werte deuten auf höhere Einnahmen, negative auf höhere Ausgaben hin.
- **Karte:** Visualisiert den **Monat** mit dem **besten Ergebnis** im gewählten Zeitraum.
- **Gruppiertes Balkendiagramm:** Vergleicht Einnahmen und Ausgaben nebeneinander.
- **Ringdiagramm:** Stellt **Fixkosten, variable Kosten und Sparrate** sowohl als **Summen** als auch als **Prozentanteil** dar.
- **Linien- und gestapeltes Säulendiagramm:** Zeigt Einnahmen als Linie und Ausgaben als Säulen über die Zeit, wodurch Monatsverläufe und **Abweichungen zwischen Einnahmen und Ausgaben direkt sichtbar** sind.

Insgesamt bietet die erste Dashboard-Seite eine kompakte, **interaktive** und **aussagekräftige Gesamtübersicht**, die als **Einstiegspunkt für weiterführende Detailanalysen** dient.

### Seite 2: Ausgabenanalyse

![Dashboard Seite 2](/Dashboard_Seite_2.png)

Die zweite Seite des Dashboards ermöglicht eine detaillierte Analyse der **Ausgaben**. Wie auf der ersten Seite stehen **Jahres- und Monat-Slicer** zur Verfügung, die alle Visuals zeitbasiert filtern.

- **Kategorien-Slicer:** Ermöglicht die Auswahl einzelner **Ausgabenkategorien**. Die Filter wirken auf alle Visuals, sodass Analysen auf **gesamte Ausgaben** oder einzelne Kategorien fokussiert werden können.
- **Karte Gesamtausgaben:** Zeigt die **Summe der Ausgaben** im gewählten Zeitraum. Ein **prozentualer Vergleich zum Vormonat** wird zusätzlich dargestellt:
    - **Blau:** Ausgaben haben sich verringert (**positiv**).
    - **Orange:** Ausgaben haben sich erhöht (**negativ**).
- **Linien- und gestapeltes Säulendiagramm:** Visualisiert die **monatlichen Ausgaben** als Säulen und den **durchschnittlichen Ausgabenwert** als Linie. So werden **Abweichungen vom Durchschnitt** sowie **Ausgaben-Spitzen und -Tiefs** direkt sichtbar.
- **Ringdiagramm nach Kategorien:** Zeigt die **Verteilung der Ausgaben** auf alle Kategorien.
- **Gestapeltes Säulendiagramm nach Wochentagen:** Analysiert, an welchen **Tagen** besonders viele Ausgaben angefallen sind.
- **Tabelle Veränderung zum Vormonat:** Listet jede Kategorie, in der Ausgaben angefallen sind, inklusive:
    - Absoluter **Veränderung zum Vormonat** (orange bei Anstieg, blau bei Rückgang, schwarz bei keiner Veränderung).
    - **Prozentuale Veränderung zum Vormonat** mit derselben Farblogik. Das Feld wird als leer angezeigt, wenn es im Vormonat keine Kosten in der Kategorie gab.

Diese Seite erlaubt eine feingranulare Analyse der Ausgaben nach Kategorien und unterstützt die gezielte Kostenkontrolle.

### Seite 3: Einnahmen- und Sparanalyse

![Dashboard Seite 2](/Dashboard_Seite_3.png)

Die dritte Seite des Dashboards bietet eine **detaillierte Analyse der Einnahmen** und **Sparaktivitäten**. **Jahres- und Monat-Slicer** ermöglichen eine zeitbasierte Filterung aller Visuals.

- **Karte Gesamteinnahmen:** Zeigt die Summe der Einnahmen im gewählten Zeitraum. Ein prozentualer Vergleich zum Vormonat wird dargestellt:
**Blau:** Einnahmen sind gestiegen.
**Orange:** Einnahmen sind gesunken.
- **Karte bester Monat:** Visualisiert den Monat mit den höchsten Einnahmen im gewählten Zeitraum.
- **Linien- und gestapeltes Säulendiagramm Einnahmen:** Zeigt die monatlichen Einnahmen als Säulen und die **durchschnittlichen Einnahmen** als Linie. So werden **Abweichungen vom Durchschnitt, Spitzenmonate und schwache Monate** direkt sichtbar.
- **Ringdiagramm nach Einnahmekategorien:** Stellt die **Verteilung der Einnahmen** auf die verschiedenen Kategorien dar, sowohl absolut als auch prozentual.
- **Liniendiagramm Einnahmensentwicklung:** Visualisiert die **Entwicklung der Einnahmen**, um Trends und saisonale Muster zu erkennen.
- **Linien- und gestapeltes Säulendiagramm Sparrate:** Zeigt die **monatlichen Sparbeträge** als Säulen und den **durchschnittlichen Sparwert** als Linie, um **Abweichungen und Sparpotenziale** zu erkennen.
- **Gestapeltes Säulendiagramm Sparverteilung:** Analysiert, wie das gesparte Geld verwendet wurde, z. B. **Investitionen** (ETFs, Aktien etc.) oder **Festgeldkonten**, und visualisiert die **Kategorien innerhalb des Sparbetrags**.

Diese Seite ermöglicht einen **umfassenden Überblick** über die Einnahmen.

## Excel Datenquelle

Die **Excel-Datenquelle** bildet die **zentrale Grundlage** für das Power-BI-Dashboard und dient der **strukturierten Erfassung von Einnahmen, Ausgaben** und **Sparvorgängen**. Die Datenpflege erfolgt **vollständig manuell** in der Excel-Datei, während die Verarbeitung, Aggregation und Visualisierung im Dashboard **vollautomatisiert** abläuft.

Ein **einheitliches Tabellenlayout**, vordefinierte **Dropdowns** sowie klar definierte **Kategorien und Kostenarten** stellen eine **konsistente, valide und fehlerarme Datenerfassung** sicher.

Die Excel-Struktur ist darauf ausgelegt, Daten **schnell** und **effizient** zu erfassen und bildet die Grundlage für eine **zuverlässige, flexible und skalierbare Analyse** im Power-BI-Dashboard.

Die Tabellen sind so aufgebaut, dass vor allem **CSV-Daten aus Kontoauszügen** effizient per **Copy-&-Paste** übernommen werden können.

### Seite 1: Landing Page

![Dashboard Seite 2](/Excel_Seite_1.png)

Die **Landing Page der Excel-Datenquelle** dient als **zentrale Einstieg- und Orientierungshilfe.** Auf der linken Seite befindet sich ein Navigationsmenü, über das zwischen den einzelnen Tabellenblättern gewechselt werden kann. Das Menü umfasst die Bereiche **Willkommen (Landing Page), Einnahmen, Ausgaben, Sparen** sowie die **Dropdowns**, die für die Datenvalidierung in den jeweiligen Tabellen genutzt werden. Dieses ist auch auf allen weiteren Seiten eingebunden.

Auf der Landing Page selbst ist eine **kurze Anleitung zur Nutzung und Pflege der Excel-Datei** hinterlegt. Diese beschreibt, wie die Daten strukturiert eingegeben werden müssen, damit das **Power-BI-Dashboard die Informationen korrekt und automatisiert verarbeitet.**

Die Datenpflege erfolgt vollständig **manuell in der Excel-Datei**, während die Weiterverarbeitung im Dashboard **vollautomatisiert** abläuft. Dadurch wird eine **einfache, konsistente und fehlerarme Datenerfassung** sichergestellt.

### Seite 2: Einnahmen

![Dashboard Seite 2](/Excel_Seite_2.png)

Die Seite **Einnahmen** dient der **strukturierten Erfassung aller Einnahmen** als Grundlage für die Auswertungen im Power-BI-Dashboard. Die Tabelle besteht aus fünf Spalten: **Einnahmen-ID, Titel, Kategorie, Betrag** und **Datum**. Diese klare Struktur stellt eine **eindeutige Zuordnung und zeitliche Auswertbarkeit** sicher.

### Seite 3: Ausgaben

![Dashboard Seite 2](/Excel_Seite_3.png)

Die Seite **Ausgaben** dient der **strukturierten Erfassung** aller Ausgaben als Datenbasis für das Power-BI-Dashboard. Die Tabelle umfasst die Spalten **Ausgaben-ID, Titel, Kategorie, Kostenart** (Unterscheidung zwischen Fixkosten und variablen Kosten), **Betrag** sowie **Datum**. Diese Struktur ermöglicht eine **differenzierte Auswertung nach Kostenarten, Kategorien** und **Zeiträumen**.

### Seite 4: Sparen

![Dashboard Seite 2](/Excel_Seite_4.png)

Die Seite **Sparen** dient der **strukturierten Erfassung aller Sparvorgänge** als Grundlage für die Analyse der Sparquote im Power-BI-Dashboard. Die Tabelle besteht aus den Spalten **Sparen-ID, Titel, Kategorie, Betrag** und **Datum**. Diese Struktur ermöglicht eine **zeitliche und kategorienbasierte Auswertung** der Sparaktivitäten.

### Seite 5: Dropdowns

![Dashboard Seite 2](/Excel_Seite_5.png)

Die Seite **Dropdowns** bildet die **zentrale Steuerungs- und Konfigurationsbasis** für die Excel-Datenquelle. Hier werden alle Kategorien und Auswahlwerte definiert, die in den Tabellen **Einnahmen, Ausgaben** und **Sparen** verwendet werden.

Vordefiniert sind die **Kostenarten** (Fixkosten, variable Kosten) sowie die **Spar-Kategorien** Festgeld und Investitionen. Diese Einträge können bei Bedarf **angepasst oder erweitert** werden.

Besonders wichtig ist die **individuelle Pflege der Einnahmen- und Ausgabenkategorien**. Diese sollten **vor der Erfassung von Einnahmen, Ausgaben und Sparvorgängen** eingerichtet werden, um eine **konsistente Datenerfassung** und eine **korrekte Auswertung** im Power-BI-Dashboard sicherzustellen.

## Skills

## Abschluss