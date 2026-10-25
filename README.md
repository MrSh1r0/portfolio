# Tung Thanh Dao — Portfolio

Persönliches Portfolio von Tung Thanh Dao. Die einseitige Website stellt die
aktuelle Werkstudententätigkeit in Systemadministration und KI, den Aufbau und
Betrieb lokaler LLM-Infrastruktur, Elektrotechnik und Informatik sowie
ausgewählte Projekte vor. Berufserfahrung und Ausbildung sind als separate
Spalten dargestellt.

Das In-house-Homelab verbindet Home Assistant, Tailscale, AdGuard,
Matter/Thread und lokale KI für Smart-Home-Automatisierung und Coding.

## Live ansehen

[mrsh1r0.github.io/portfolio](https://mrsh1r0.github.io/portfolio/)

## Technologie

- Semantisches HTML5
- Responsives CSS
- Statische Bereitstellung über GitHub Pages
- GitHub Actions für den automatischen Deploy

Die Website benötigt kein Framework, keine Build-Schritte und keine
JavaScript-Abhängigkeiten.

## Lokal starten

`index.html` direkt im Browser öffnen oder im Repository-Verzeichnis einen
lokalen Webserver starten:

```sh
python3 -m http.server 8000
```

Anschließend <http://localhost:8000> öffnen.

## Inhalte bearbeiten

- Texte, Abschnitte, Navigation und Metadaten: `index.html`
- Layout, Farben und responsive Regeln: `styles.css`
- Profilbilder: `assets/`

Die Inhalte sind auf Deutsch. Alle öffentlichen GitHub-Repositories sind im
Projektbereich direkt verlinkt. Projekte ohne öffentliches Repository werden
als solche gekennzeichnet. Keine privaten Zugangsdaten, Netzwerkdetails oder
internen Systeminformationen gehören in die öffentliche Projektbeschreibung.

## Datenschutz

- Die E-Mail-Kontaktoption ist auf ausdrücklichen Wunsch öffentlich. Sie ist
  als `mailto`-Link eingebunden und kann daher von Scraping-Bots ausgelesen
  werden.
- Telefonnummern und Wohnadresse werden nicht auf der Website veröffentlicht.
- Arbeitgeber und Hochschulen sind im Werdegang mit den vom Inhaber
  bereitgestellten Namen aufgeführt.
- Zusätzlich ist Kontakt über das öffentliche
  [GitHub-Profil](https://github.com/MrSh1r0) möglich.
- Die Seite setzt `noindex`- und `nofollow`-Anweisungen für regelkonforme
  Suchmaschinen. Diese Anweisungen verhindern nicht, dass Dritte öffentliche
  Inhalte abrufen oder kopieren.

## Öffentliches Profilbild

- `assets/github-profile.jpg` — öffentliches Profilbild im Profilabschnitt und
  als Vorschaubild beim Teilen der Website. Es verlinkt auf das
  [GitHub-Profil MrSh1r0](https://github.com/MrSh1r0).
- Das offizielle Portrait ist nicht Teil der Website.

## Projektstruktur

```text
.
├── .github/workflows/deploy.yml  # GitHub-Pages-Deployment
├── assets/                       # Profilbilder
├── index.html                    # Portfolio-Inhalte und Struktur
├── styles.css                    # Gestaltung und mobile Layouts
└── README.md
```

## Deployment

Der Workflow `.github/workflows/deploy.yml` veröffentlicht die Website bei
jedem Push auf `main` und kann unter **Actions** manuell gestartet werden.
GitHub Pages muss in **Settings → Pages → Build and deployment** auf
**GitHub Actions** eingestellt sein.

Die klare Trennung von Profil, Ausbildung, Erfahrung, Projekten und Kontakt
orientiert sich an der Struktur des
[jandarn/portfolio](https://github.com/jandarn/portfolio); dieses Projekt
bleibt eine eigenständige, frameworkfreie Umsetzung.
