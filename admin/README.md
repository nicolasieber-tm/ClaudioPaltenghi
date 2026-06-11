# Paltenghi Claudio – Admin-Backend (Skizze)

Einfache HTML-Skizze für das Verwaltungs-Backend des individuellen Buchungssystems:
Dashboard, Termine/Buchungen, Angebote & Preise sowie Kalender-Verbindung
(Angebot → Unterkalender, Verfügbarkeit).

Visuell an die bestehende Website-Skizze (`../index.html`) angeglichen –
gleiche Schrift (Archivo / Archivo Expanded), monochromes Schwarz/Weiss-Design.

Reine Vorschau/Referenz – keine echte Datenspeicherung, keine echte Kalender-Anbindung.
Buttons zeigen Demo-Meldungen.

## Lokal starten

```bash
cd admin
npm start
# -> http://localhost:3000
```

(Node 18+ nötig, keine Abhängigkeiten zu installieren.)

Alternativ kann `admin/index.html` direkt im Browser geöffnet werden.

## Dateien

- `index.html` – komplette Admin-Skizze (HTML/CSS/JS in einer Datei)
- `server.js` – minimaler statischer Webserver (zero-dependency)
- `package.json` – Start-Skript
