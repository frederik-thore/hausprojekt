# Unser Haus · Planungsatlas

Öffentliche Übersicht: https://frederik-thore.github.io/hausprojekt/

13 Bereiche, 100 Ansichten. Planungsstand 64, basierend auf dem vollständigen Hausmodell 63. Das Arbeitszimmer enthält die Varianten Alltag mit Concept2 und Gäste mit 140 × 200 cm Bett, erhöhtem Tisch und eingeschobenem Stuhl.

## Änderungswünsche

Eine Ansicht öffnen, „Stelle im Bild markieren“ wählen, ins Bild klicken und den Wunsch beschreiben. „Auf GitHub einreichen“ öffnet einen vorausgefüllten Issue-Entwurf; erst das Absenden auf GitHub macht ihn gemeinsam sichtbar. Dafür ist ein GitHub-Konto erforderlich. Browserentwürfe sind lokal und werden nicht zwischen Geräten synchronisiert. Alternativ den JSON-Entwurf herunterladen und weitergeben.

Die Seite ist eine Rendergalerie, kein 3D-Editor. Möbeländerungen erfolgen im Hausmodell. Raum, Variante, Bild-ID und relative Markierungskoordinaten ordnen jeden Wunsch eindeutig zu.

## Aktualisieren

- `manifest.json` dokumentiert Räume, Fakten und Ansichten. `data.js` enthält dieselben Daten als Browser-Script.
- Bilder liegen in `images/`: `<bild-id>.webp` (1800 × 1200) und `<bild-id>-thumb.webp` (720 × 480).
- Für einzelne Räume nur die betroffenen Bilder und gegebenenfalls Fakten ersetzen. Bestehende Bild-IDs behalten; bei inhaltlich neuer Perspektive eine neue ID vergeben.
- Versionsnummer und Datumsangaben bei neuen Modellständen gemeinsam aktualisieren. Frühere Stände bleiben in der Git-Historie erhalten.
- GitHub Pages veröffentlicht aus dem Root-Verzeichnis des Branches `main`. Keine Zugangsdaten oder Build-Dienste nötig.
- Lokal: `python3 -m http.server 8764`, anschließend `http://localhost:8764` öffnen.

Alle Maße sind Planungsangaben. Orthografische Geschossansichten verwenden die vereinfachte Darstellung des vorhandenen Übersichtsmodells. Weitwinkel können räumliche Abstände größer erscheinen lassen. Visualisierungen ersetzen keine Ausführungsplanung.
