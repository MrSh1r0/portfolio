# Tung Thanh Dao — Portfolio

Persönliches Portfolio von Tung Thanh Dao. Die einseitige Website stellt die
aktuelle Werkstudententätigkeit in Systemadministration und KI, den Aufbau und
Betrieb lokaler LLM-Infrastruktur, Elektrotechnik und Informatik sowie
ausgewählte Projekte vor.

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

Die Inhalte sind auf Deutsch. Projekte ohne öffentliches Repository werden
vorgestellt, aber nicht als öffentliche GitHub-Repositories verlinkt. Keine
privaten Zugangsdaten, Netzwerkdetails oder internen Systeminformationen
gehören in die öffentliche Projektbeschreibung.

## Datenschutz

- Es werden keine E-Mail-Adresse, Telefonnummer, Arbeitgeber, genauen
  Bildungsorte oder Wohnorte auf der Website veröffentlicht.
- Kontakt ist ausschließlich über das öffentliche
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
