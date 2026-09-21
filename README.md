# bauwerkpartner Website v2

Statische Single-Page-Website (Test-/Demo-Stand). Keine Build-Tools, keine Abhängigkeiten.

## Struktur

```
index.html      komplette Seite (HTML, CSS, JS inline)
img/            wird zur Laufzeit geladen — muss mit hochgeladen werden
img/            Logo-Varianten und Referenzfotos
```

## Deploy

**GitHub Pages** — Repository anlegen, Inhalt dieses Ordners in den Root pushen,
dann Settings → Pages → Branch `main`, Ordner `/ (root)`.

**Vercel** — Ordner importieren, Framework Preset „Other", kein Build-Command,
Output Directory `.`

Lokal: `index.html` im Browser öffnen.

## Hinweise

- Das Kontaktformular ist ein Demo-Formular und versendet nichts. Vor dem
  Live-Gang an einen Mail-Endpunkt anbinden.
- Der Demo-Hinweisbalken oben lässt sich im Quelltext entfernen (Suche nach
  `TEST-/DEMO-WEBSITE`).
- Impressum und Datenschutz im Footer sind noch Platzhalter ohne Inhalt.
- Bildrechte prüfen: `img/statistisches-bundesamt.jpg` ist mit
  „© Statistisches Bundesamt" ausgewiesen.
- Responsiv: Layout erkennt automatisch die Bildschirmbreite (Umschaltpunkt 860 px).
  Unter 860 px Burger-Menü, 2x2-Karten und Vollbild-Panels; darüber Desktop-Layout.
- Schriften (Barlow Condensed, IBM Plex Sans) werden von Google Fonts geladen.
  Für DSGVO-Konformität lokal einbinden.
