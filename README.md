# Huschels Touren Cockpit V0.1.0

Zentraler Überbau für Peters Reise-Workflow:

1. Recherche mit ChatGPT
2. Route in Kurviger
3. GPX ins Cockpit
4. Tour Navigator Modern bearbeiten
5. Reiseplanungs-JSON / Wildhogs Reiseführer
6. gefahrene GPX
7. finaler Tour Animator

## Direkte Browser-Übergaben

Wenn das Cockpit ebenfalls unter `phusch.github.io` veröffentlicht wird, teilt es den Browser-Speicher mit den bestehenden Apps.

- Tour Navigator: `tourNavigatorModern.lastRoute.v1`
- Tour Animator: `tourNavigator.animationRoute`
- Cockpit: `huschelsTourenCockpit.project.v1`

## V0.1.0

- Projektverwaltung
- 7-Schritt-Workflow
- großer „Nächster Schritt“-Button
- ChatGPT-Rechercheauftrag kopieren
- Kurviger öffnen
- geplante und gefahrene GPX einlesen
- GPX in Tour-Navigator-kompatible Punkte konvertieren
- Route an Tour Navigator übergeben
- aktuellen Navigator-Stand zurückholen
- finale Route an Tour Animator übergeben
- Tour-Navigator-/Reiseplanungs-/Cockpit-JSON importieren
- komplette Cockpit-Projektdatei exportieren
- App-Links über Zahnrad konfigurierbar

Empfohlener Repo-Name: `huschels-touren-cockpit`
GitHub Pages: `https://phusch.github.io/huschels-touren-cockpit/`
