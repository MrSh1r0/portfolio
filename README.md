# Tung Thanh Dao — Portfolio

Eine responsive, statische Portfolio-Website auf Deutsch. Sie stellt Tung Thanh
Dao und seine Arbeit in Systemadministration, IT-Support, KI, MDM und
Intranet-Webentwicklung bei THEES+PARTNER in Trier vor.

## Lokal ansehen

Die Website benötigt weder Build-Schritt noch zusätzliche Abhängigkeiten.
`index.html` direkt im Browser öffnen oder im Repository-Verzeichnis einen
statischen Webserver starten:

```sh
python3 -m http.server 8000
```

Danach `http://localhost:8000` öffnen.

## Auf GitHub Pages veröffentlichen

Der Workflow unter `.github/workflows/deploy.yml` veröffentlicht den Inhalt
dieses Repositorys bei jedem Push auf `main` und kann auch manuell gestartet
werden.

1. Den Branch `main` zu GitHub pushen.
2. Im Repository unter **Settings → Pages → Build and deployment** als Quelle
   **GitHub Actions** auswählen.
3. Den erfolgreichen Lauf unter **Actions** abwarten. GitHub zeigt die
   veröffentlichte URL im Deployment an. Für dieses Repository ist die URL
   üblicherweise `https://mrsh1r0.github.io/portfolio/`.

## Inhalt aktualisieren

- Texte, Projekte, Kontakt und Navigation: `index.html`
- Gestaltung und responsive Layouts: `styles.css`
- Die Projekte ohne öffentliche Repository-Links sind im Lebenslauf genannt;
  private Projekte werden nicht als öffentlich verlinkt dargestellt.
