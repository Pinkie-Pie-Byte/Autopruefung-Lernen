# 🚗 Auto Theorie CH – Lern-App (asa-Standard)

Eine moderne, blitzschnelle und **100 % offlinefähige Web-App (PWA)** zur optimalen Vorbereitung auf die **Schweizer Autoprüfung (Kategorie B)** im offiziellen **asa-Format**.

Entwickelt für Desktop und Smartphones mit nativer App-Haptik.

---

## 🌟 Highlights & Funktionen

- **385 fundierte Übungsfragen:** Deckt alle prüfungsrelevanten Bereiche des Schweizer Strassenverkehrsrechts ab.
- **Offizieller asa-Prüfungsmodus:**
  - 50 zufällige Prüfungsfragen
  - 45-Minuten-Countdown (visuelle Warnung unter 5 Minuten)
  - Maximal 15 Fehlerpunkte zum Bestehen
  - Realistische Punkte- und Zeitberechnung
- **Lernen nach Themen:** 26 strukturierte Kategorien mit individuellen Fortschrittsbalken.
- **Fundierte Erklärungen mit Gesetzesbezug:** Jede Frage enthält die genaue Begründung und referenziert die offiziellen Artikel aus **SVG**, **VRV**, **SSV** oder **VTS**.
- **Detaillierte Fehlerauswertung:** Falsch beantwortete Fragen werden gespeichert und können gezielt wiederholt werden – inklusive optischer Kennzeichnung deiner falschen Wahl vs. der richtigen Lösung.
- **100 % Offline-Fähig:** Alle 59 offiziellen Schweizer Verkehrsschild-Grafiken sind als Vektoren direkt eingebettet. Funktioniert komplett ohne Internetverbindung im Zug, Flugzeug oder Funkloch.
- **Progressive Web App (PWA):** Kann mit einem Klick als App auf den Startbildschirm (iOS & Android) installiert werden.
- **Datenschutz & Persistenz:** Speichert deinen gesamten Lernfortschritt sicher und lokal im Browser (`localStorage`). Kein Login, kein Tracking, keine Werbung.

---

## 🚦 Themenbereiche (26 Kategorien)

1. Vortritt & Verzweigungen *(Rechtsvortritt, abknickende Hauptstrassen, Kreisel)*
2. Signale & Markierungen *(Gefahren-, Vorschrifts- und Hinweissignale, Linien)*
3. Autobahn & Autostrasse *(Rechtsfahrgebot, Pannenstreifen, Einfädeln)*
4. Geschwindigkeit & Abstand *(2-Sekunden-Regel, Faustformeln)*
5. Beleuchtung & Lichtsignale *(Lichtpflicht, Nebelleuchten, Polizisten-Handzeichen)*
6. Fahrphysik, Bremsen & Anhalteweg *(Aquaplaning, ABS, ESP)*
7. Alkohol & Fahrunfähigkeit *(Grenzwerte, Neulenker 0.1 ‰ vs. 0.5 ‰)*
8. Halten & Parkieren *(Blaue Zone, Parkscheibe, Parkverbote)*
9. Tunnel & Sicherheit *(Verhalten bei Brand, Panne, Notausgänge)*
10. Ausweise, Lernfahrten & L-Schild *(Begleitperson-Vorschriften)*
11. Reifen & Räder *(Mindestprofiltiefe, Schneeketten, Spikes)*
12. Tram & ÖV *(Vorrangregeln für Schienenfahrzeuge)*
13. Besondere Verkehrsteilnehmer *(Fussgänger, Radfahrer, E-Bikes)*
14. Beladung & Anhänger *(Dachlasten, Überhang-Kennzeichnung)*
15. Umwelt, Lärm & Notfall / Erste Hilfe

---

## 📱 Als App auf dem Smartphone installieren

### iPhone / iPad (Safari)
1. Die Seite in **Safari** aufrufen.
2. Unten auf den **Teilen-Button** *(Viereck mit Pfeil nach oben)* tippen.
3. Im Menü auf **„Zum Home-Bildschirm“** tippen.
4. Fertig! Die App hat ihr eigenes Schweizer Icon und öffnet sich im Vollbild ohne Browserleiste.

### Android (Chrome / Samsung Internet)
1. Die Seite in **Chrome** öffnen.
2. Oben rechts auf das **Drei-Punkte-Menü** tippen.
3. Auf **„App installieren“** oder **„Zum Startbildschirm hinzufügen“** tippen.

---

## 🚀 Deployment / Veröffentlichung

Da die gesamte Anwendung aus statischen Dateien (`index.html`, `manifest.json`, `sw.js`, `icon.svg`, `img/`) besteht, lässt sie sich in Sekunden kostenlos hosten:

### 1. GitHub Pages
- In den Repository-Einstellungen (**Settings ➔ Pages**) unter **Source** den Branch `main` auswählen und speichern.
- Live unter: `https://<dein-username>.github.io/<repo-name>/`

### 2. Netlify (Drag & Drop)
- Auf [app.netlify.com/drop](https://app.netlify.com/drop) gehen.
- Den Projektordner einfach per Drag & Drop in den Browser ziehen.
- Fertig!

---

## 🛠️ Technische Details

- **Architektur:** Vanilla HTML5, modernes CSS3 (CSS Variables, Flexbox, Grid), JavaScript (ES6+).
- **Abhängigkeiten:** Keine (Zero Dependencies – kein Node.js-Buildschritt, kein Framework-Overhead).
- **Service Worker:** Native Caching-Strategie (`sw.js`) für sofortiges Laden und Offline-Nutzung.
- **Größe:** Die gesamte App wiegt inklusive aller Daten und hochauflösenden Vektor-Grafiken nur rund 1.3 MB.

---

## 📄 Lizenz & Haftungsausschluss

Dieses Projekt dient ausschliesslich zu privaten Lern- und Übungszwecken. Die Fragen und Antworten orientieren sich an den offiziellen Bestimmungen der Vereinigung der Strassenverkehrsämter (asa) sowie dem Schweizer Strassenverkehrsgesetz (SVG) und seinen Verordnungen (VRV, SSV, VTS). Für die Aktualität, Vollständigkeit und das Bestehen der amtlichen Theorieprüfung wird keine Gewähr übernommen.
