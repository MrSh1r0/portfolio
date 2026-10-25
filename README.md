# Tung Thanh Dao — Portfolio

Persönliches Portfolio von Tung Thanh Dao, Werkstudent für
Systemadministration und KI bei THEES+PARTNER in Trier. Die einseitige Website
stellt Profil, Berufserfahrung, Ausbildung, Projekte und Kontakt vor.

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

Die Inhalte sind auf Deutsch. Im Lebenslauf genannte Projekte ohne öffentliches
Repository werden vorgestellt, aber nicht als öffentliche GitHub-Repositories
verlinkt.

## Öffentliches Profilbild

- `assets/github-profile.jpg` — öffentliches Profilbild im Profilabschnitt und
  als Vorschaubild beim Teilen der Website. Es verlinkt auf das
  [GitHub-Profil MrSh1r0](https://github.com/MrSh1r0).
- Das offizielle Portrait wird nicht auf der öffentlichen Website verwendet.

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
