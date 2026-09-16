# bauwerkpartner GmbH – Website

Statische HTML/CSS-Website für bauwerkpartner GmbH.

## Projektstruktur

- `index.html` – Startseite
- `unternehmen.html` – Unternehmen
- `leistungen.html` – Leistungen
- `referenzen.html` – Referenzen
- `kontakt.html` – Kontakt
- `impressum.html` – Impressum
- `datenschutz.html` – Datenschutz
- `css/style.css` – Stylesheet
- `img/` – Bilder und Logo

## GitHub

Das **gesamte Repository** sollte den Inhalt dieses Ordners enthalten. `index.html` liegt absichtlich direkt im Repository-Root.

```text
bauwerkpartner-gmbh/
├── index.html
├── unternehmen.html
├── leistungen.html
├── referenzen.html
├── kontakt.html
├── impressum.html
├── datenschutz.html
├── css/
│   └── style.css
└── img/
    └── ...
```

## Vercel

Beim Import des GitHub-Repositories in Vercel:

- **Framework Preset:** Other / kein Framework
- **Root Directory:** `.` (Repository-Root)
- **Build Command:** leer lassen
- **Output Directory:** leer lassen
- **Install Command:** leer lassen

Danach deployen. Die Startseite wird über `index.html` ausgeliefert.

## Hinweis zur Übergabe

Vor dem Livegang bitte insbesondere Impressum, Datenschutzerklärung, Kontaktdaten, Telefonnummer, E-Mail-Adresse und rechtliche Pflichtangaben auf Aktualität prüfen.
