# Unser Haus · Planungsatlas

Öffentliche Übersicht: https://frederik-thore.github.io/hausprojekt/

13 Bereiche, 111 Ansichten. Planungsstand 70 vom 22. Oktober 2026. Das Arbeitszimmer enthält die Varianten Alltag mit Concept2 und Gäste mit 140 × 200 cm Bett, erhöhtem Tisch und eingeschobenem Stuhl.

## Nutzung

Räume auswählen, Ansichten nach Bildausschnitt filtern und Bilder vergrößern. In der Bildansicht mit den Pfeilen durch den Raum blättern. Für das Arbeitszimmer stehen Alltag und Gästebett zur Auswahl. Zum Anschauen ist kein Login nötig. Möbeländerungen erfolgen weiterhin im Hausmodell.

## Aktualisieren

- `manifest.json` dokumentiert Räume, Fakten und Ansichten. `data.js` enthält dieselben Daten als Browser-Script.
- Bilder liegen in `images/`: `<bild-id>.webp` (1800 × 1200) und `<bild-id>-thumb.webp` (720 × 480).
- Für einzelne Räume nur die betroffenen Bilder und gegebenenfalls Fakten ersetzen. Bestehende Bild-IDs behalten; bei inhaltlich neuer Perspektive eine neue ID vergeben.
- Versionsnummer und Datumsangaben bei neuen Modellständen gemeinsam aktualisieren. Frühere Stände bleiben in der Git-Historie erhalten.
- GitHub Pages veröffentlicht aus dem Root-Verzeichnis des Branches `main`. Keine Zugangsdaten oder Build-Dienste nötig.
- Lokal: `python3 -m http.server 8764`, anschließend `http://localhost:8764` öffnen.

Alle Maße sind Planungsangaben. Orthografische Geschossansichten verwenden die vereinfachte Darstellung des vorhandenen Übersichtsmodells. Weitwinkel können räumliche Abstände größer erscheinen lassen. Visualisierungen ersetzen keine Ausführungsplanung.

Stand 70: Im Schlafzimmer ist die frühere Variante 4 mit zugesägter hoher GULLABERG-Tür festgelegt, im Familienbad die Ausführung mit zwei 40-cm-Hochschränken und 10 cm Wandabstand. Die übrigen Optionen werden nicht mehr angezeigt.

Der HWR zeigt HAVSTORP beige, HAMPHULT-Eichengriffe, Siemens WG44G2Z40 / WT47R440, Vaillant uniTOWER VIH QW 190/7 E 18L, den ausgerichteten Batteriespeicher und einen beispielhaften Elektroschrank am HA-Platz.

Produktgrundlagen HWR: [Waschmaschine WG44G2Z40](https://media3.bsh-group.com/Documents/specsheet/de-DE/WG44G2Z40.pdf), [Trockner WT47R440](https://media3.bsh-group.com/Documents/specsheet/de-DE/WT47R440.pdf). Der Elektroschrank ist als Platzhalter für die spätere Elektroplanung modelliert.
