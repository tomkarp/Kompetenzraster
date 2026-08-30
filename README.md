# Kompetenzraster

Web-App zum Sammeln und Strukturieren von Kompetenzformulierungen.

## Funktionen

- beliebig viele Kompetenzbereiche und Kompetenzstufen
- Kompetenzen mit Beschreibung, Voraussetzungen, Material und Bemerkungen
- Drag-and-drop innerhalb eines Bereichs, zwischen Stufen und zwischen Bereichen
- Voraussetzungen per Klick auf vorhandene Kompetenzen
- JSON-Import und -Export
- Export als eigenständige HTML-Tabelle für Moodle
- Speicherung im Browser über `localStorage`

## Verwendung

`index.html` im Browser öffnen. Die Anwendung benötigt keinen Server und keine externen Bibliotheken.

Die JSON-Datei ist das vollständige Datenmodell. Kompetenzen referenzieren Voraussetzungen über deren `id`.
