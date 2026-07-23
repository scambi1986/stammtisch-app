# Hundefreunde Hasloh – Stammtisch-App auf GitHub Pages

Diese App ist ein fertiges, statisches Paket. Kein Programmieren, kein Terminal nötig – alles läuft über die GitHub-Webseite.

## Was ist in diesem Ordner
- `index.html` – die App selbst
- `support.js`, `image-slot.js` – Laufzeit-Dateien, die die App braucht
- `manifest.webmanifest`, `sw.js`, `icons/` – machen die App installierbar & offline-fähig
- `README.md` – diese Anleitung

**Wichtig:** Beim Hochladen müssen alle Dateien/Ordner genau so wie hier vorliegen – nicht nur `index.html` allein hochladen.

## Schritt 1 – GitHub-Konto & Repository
1. Falls noch nicht vorhanden: kostenlos registrieren auf [github.com](https://github.com).
2. Oben rechts auf das **„+"** klicken → **„New repository"**.
3. Repository-Name vergeben, z. B. `stammtisch-app`.
4. Sichtbarkeit auf **Public** stellen (für kostenloses GitHub Pages nötig).
5. Nichts weiter ankreuzen (kein README hinzufügen) → **„Create repository"**.

## Schritt 2 – Dateien hochladen
1. Im neu erstellten (leeren) Repository auf **„uploading an existing file"** klicken
   (oder oben auf **„Add file" → „Upload files"**).
2. Alle Dateien und Ordner aus diesem `github-pages`-Paket dorthin ziehen
   (also `index.html`, `support.js`, `image-slot.js`, `manifest.webmanifest`, `sw.js` und den ganzen `icons`-Ordner).
   - Tipp: Zieht am besten den **Inhalt** des Ordners hinein, nicht den Ordner `github-pages` selbst –
     `index.html` muss direkt im Hauptverzeichnis des Repositories liegen.
3. Unten bei „Commit changes" auf **„Commit changes"** klicken.

## Schritt 3 – GitHub Pages aktivieren
1. Im Repository oben auf **„Settings"** klicken.
2. Im linken Menü auf **„Pages"** klicken.
3. Bei **„Build and deployment" → „Source"** die Option **„Deploy from a branch"** wählen.
4. Bei **„Branch"**: `main` auswählen, Ordner `/ (root)` lassen → **„Save"**.
5. Kurz warten (meist 1–2 Minuten). Danach erscheint oben ein grüner Kasten mit der Live-URL,
   z. B. `https://<dein-username>.github.io/stammtisch-app/`.

## Schritt 4 – Auf dem Handy installieren
1. Die URL aus Schritt 3 auf dem Handy im Browser öffnen (Safari bei iPhone, Chrome bei Android).
2. **iPhone (Safari):** Teilen-Symbol → „Zum Home-Bildschirm".
3. **Android (Chrome):** Menü (drei Punkte) → „Zum Startbildschirm hinzufügen" / „App installieren".
4. Die App liegt danach wie eine normale App auf dem Homescreen und funktioniert auch offline.

## Änderungen später aktualisieren
Wenn ich euch eine neue Version der App gebe: einfach die geänderten Dateien im Repository
erneut hochladen (gleicher Weg wie Schritt 2, GitHub fragt automatisch, ob bestehende Dateien
ersetzt werden sollen). GitHub Pages aktualisiert sich dann automatisch nach ein bis zwei Minuten.

## Google-Sheet-Anbindung (Statistik)
Falls ihr das Google-Sheet-Backend nutzt: die Web-App-URL wird direkt in der App unter
„Info → Datenanbindung" eingetragen – das ist unabhängig vom Hosting und muss nach dem
GitHub-Pages-Upload nicht erneut gemacht werden, wenn ihr denselben Browser/dasselbe Handy nutzt.
