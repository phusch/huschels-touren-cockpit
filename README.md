# Huschels Touren Cockpit V0.1.5.2

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


## V0.1.1

- Workflow-Kapitel in abgestuften Orange-/Creme-Farbtönen
- Recherchefeld startet mit einer ausfüllbaren Standard-Suchmaske
- Button-Reihenfolge in jedem Schritt chronologisch nummeriert
- Recherche explizit als 1 Kopieren → 2 ChatGPT öffnen → 3 Recherche erledigt


## V0.1.2

- Recherche startet jetzt direkt im Suchmasken-Feld
- Cursor wird automatisch in die Suchmaske gesetzt
- aktive Eingabe-/Arbeitsbereiche werden orange hervorgehoben
- Suchmaske sichtbarer beschriftet und mit Hinweis versehen
- Recherche-Zeitstrahl jetzt: 1 Suchmaske öffnen → 2 Auftrag kopieren → 3 ChatGPT öffnen → 4 Recherche erledigt


## V0.1.3

- vorhandener alter Recherche-Freitext wird automatisch in die neue Suchmaske übernommen
- Suchmaske erscheint beim Start zuverlässig auch in bestehenden Projekten
- neuer Button „Suchmaske neu einsetzen“
- Recherchefeld höher und monospace-artig für bessere Lesbarkeit

## V0.1.4

- fester Reiseplanungs-Master-Prompt dauerhaft im Cockpit
- Recherche vollständig als Formular: nur Antworten eingeben/auswählen
- Fortbewegungsmittel: Motorrad, Auto, Wohnmobil, Fahrrad, Boot, Sonstige
- Tageskilometer, Fahrzeit, Priorität, Umweg, Unterkunft, Budget, Parkplatz, Stopps, Aktivitäten und Kulinarik separat steuerbar
- dynamischer GPX-Dateiname nach Schema YYYY-MM-DD_HHMM_Projektname.gpx
- kompletter Workflow ChatGPT → Kurviger → Tour Navigator → Reiseplanungs-JSON → Wildhogs Reiseführer → gefahrene GPX → Tour Animator im Prompt verankert
- bestehende alte Freitext-Recherche wird bei Migration als Zusatzwunsch übernommen

## V0.1.5

- neuer Schritt „ChatGPT-Vorplanung“
- vorläufige ChatGPT-Reisebeschreibung separat im Cockpit archivieren
- vorläufige ChatGPT-GPX separat speichern
- diese Vorplanung wird ausdrücklich nicht an Tour Navigator übergeben
- Kurviger wird für die fahrerische Feinplanung aus diesem Zwischenschritt geöffnet
- erst die aus Kurviger zurückgeladene GPX wird zur verbindlichen Planungsroute
- nur diese Kurviger-GPX wird an Tour Navigator weitergegeben
- ChatGPT-GPX kann aus dem Cockpit erneut heruntergeladen werden
- Workflow jetzt in 8 klar getrennten Schritten


## V0.1.5.2
- Oberfläche konsequent auf den normalen Zeitstrahl reduziert
- redundante Direktübergabe-Buttons entfernt
- Datei-Uploads werden direkt aus dem passenden Workflow-Schritt geöffnet
- „Textdatei laden“, „GPX erneut herunterladen“ und andere Nebenwege entfernt
- Vorplanung als Rich-Text-Archiv mit Formatierungen, Tabellen und Bildern
- Bild hinzufügen bleibt als einzige Zusatzaktion in der Vorplanung
- V0.1.5-Workflow und Trennung Vorplanung/Kurviger/Tour Navigator bleiben erhalten
