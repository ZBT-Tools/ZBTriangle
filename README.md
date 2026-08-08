# ZBTriangle
Interactive browser tool for designing and documenting 3-component solvent compositions on a ternary diagram
ENGLISH

Ternary Solvent Designer

 Single HTML file, no installation — just open ZBTriangle.html in a browser.

 Usage
1. Name the three solvents and set constraints in the Label/Constraints tab.
2. Set a composition (click the triangle or type values) and click Save composition.
3. Repeat to build up a series of compositions.
4. Optionally add property columns and enable a heatmap or point-coloring visualization. The scale is relative by default. If multiple sets have to be compared, its recommended to adjust the scale. (Note: the heatmap is a visualization, not a model.)
5. Export the diagram/table as graph or table.
6. Import a previously saved CSV to continue a session.

Features
- Interactive triangle diagram: set composition by clicking/dragging, or by typing values (auto-normalized to 100%)
- Optional snap-to-grid (default 10% steps)
- Label/Constraints tab: name the three solvents and define min/max limits per solvent; disallowed regions are shaded on the triangle
- Save compositions to a table (editable Dispersion Nr., delete button per row, saved points shown on the triangle)
- Draggable composition info box, switchable between vertical and horizontal layout
- Properties tab: add custom measured properties per composition (e.g. "Stability Index"), entered directly in the table
- Visualize a property as a heatmap on the triangle (adjustable influence radius) and/or by coloring the saved points; choose from 3 color scales (Blue-Red, Green-Yellow-Red, Viridis); range can be automatic or manual
- Draggable color-scale legend, switchable between horizontal and vertical layout
- Export: diagram as PNG, data as CSV, or as XML (opens in Excel, numeric columns formatted as numbers)
- Import: reload a previously exported CSV, either appended to or replacing the current table
- Reset button restores all defaults

Notes
- All compositions are normalized so the three components sum to 100.
- Validity (Yes/No) is checked live against the current constraints.


++++ DEUTSCH ++++

Ternary Solvent Designer

Interaktives Browser-Tool zur Auslegung und Dokumentation von 3-Komponenten-Lösungsmittelzusammensetzungen anhand eines Dreiecksdiagramms — ZBTriangle.html einfach im Browser öffnen.

Empfohlener Workflow
1. Lösungsmittel benennen und Randbedingungen im Tab Label/Constraints festlegen.
2. Zusammensetzung einstellen und mit Save composition speichern.
3. Für eine Screening-Serie wiederholen.
4. Optional: Eigenschaftsspalten anlegen und per Heatmap oder Punktfärbung visualisieren. Ggf. die Skala definieren. 
5. Ergebnisse exportieren oder eine zuvor gespeicherte CSV-Datei zum Fortsetzen importieren.

Typische Anwendung
- Entwicklung von Katalysator- und Ionomer-/Bindertinten
- Bewertung von Lösungsmittelmischungen (Dispergierung, Benetzung, Beschichtbarkeit)
- Definition zulässiger Zusammensetzungsfenster für Labor- und Scale-up-Versuche
- Dokumentation von Screening-Serien mit mehreren Dispersionen, inkl. gemessener Eigenschaften (z. B. Stability Index)

Funktionen
- Interaktives Dreiecksdiagramm: Zusammensetzung per Klick/Ziehen oder manueller Eingabe festlegen (automatische Normierung auf 100 %)
- Optionales Snap-to-Grid (Standard: 10 %-Schritte)
- Tab Label/Constraints: Benennung der drei Lösungsmittel sowie Definition von Min-/Max-Grenzen; unzulässige Bereiche werden im Diagramm eingefärbt
- Speichern von Zusammensetzungen in einer Tabelle (Dispersion Nr. editierbar, Zeilen löschbar, alle gespeicherten Punkte gleichzeitig im Diagramm sichtbar)
- Verschiebbare Kompositions-Infobox, umschaltbar zwischen vertikalem und horizontalem Layout
- Tab Properties: eigene gemessene Eigenschaften je Zusammensetzung anlegen (z. B. "Stability Index"), Eingabe direkt in der Tabelle
- Visualisierung einer Eigenschaft als Heatmap auf dem Dreieck (Einflussradius einstellbar) und/oder als Einfärbung der gespeicherten Punkte; 3 Farbskalen wählbar (Blau-Rot, Grün-Gelb-Rot, Viridis); Wertebereich automatisch oder manuell
- Verschiebbare Farbskalen-Legende, umschaltbar zwischen horizontalem und vertikalem Layout
- Export: Diagramm als PNG, Daten als CSV oder als XML (öffnet in Excel, Zahlenspalten korrekt als Zahl formatiert)
- Import: zuvor exportierte CSV-Datei wieder einlesen, wahlweise angehängt an oder anstelle der aktuellen Tabelle
- Reset-Button setzt alle Einstellungen zurück


Hinweise
- Das Tool bewertet keine Elektrodenperformance direkt und ersetzt keine Rheologie-, Stabilitäts- oder Beschichtungsprüfung — es dient als Planungs-, Visualisierungs- und Dokumentationswerkzeug.
- Besonders sinnvoll in Kombination mit Viskositätsdaten, Stabilitätsdaten, Beschichtungsergebnissen oder EIS-/Polarisationsdaten.
