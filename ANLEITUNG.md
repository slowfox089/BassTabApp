# Bass Tabs – Installation auf GitHub Pages und dem iPad

## 1. Repository anlegen
1. Auf github.com einloggen → oben rechts **+** → **New repository**.
2. Name z. B. `bass-tabs`, Sichtbarkeit **Public** (GitHub Pages ist bei kostenlosen Accounts nur für öffentliche Repos verfügbar – deine Songs liegen trotzdem nur auf dem iPad, nicht im Repo).
3. **Create repository**.

## 2. Dateien hochladen
1. Im neuen Repo auf **uploading an existing file** klicken.
2. Alle Dateien aus dem ZIP hineinziehen (nicht den Ordner, die Dateien selbst):
   `index.html`, `sw.js`, `manifest.webmanifest`, `icon-192.png`, `icon-512.png`, `apple-touch-icon.png`
3. **Commit changes**.

## 3. GitHub Pages einschalten
1. Im Repo **Settings** → links **Pages**.
2. Bei *Source*: **Deploy from a branch**, Branch **main**, Ordner **/ (root)** → **Save**.
3. Nach ca. 1 Minute steht oben die Adresse, z. B. `https://DEIN-NAME.github.io/bass-tabs/`.

## 4. Aufs iPad
1. Die Adresse in **Safari** öffnen (nicht Chrome – nur Safari kann Web-Apps auf den Home-Bildschirm legen).
2. Teilen-Symbol → **Zum Home-Bildschirm** → **Hinzufügen**.
3. Die App einmal über das neue Icon öffnen, solange das iPad online ist. Ab dann läuft sie offline.

## Updates einspielen
1. Geänderte `index.html` im Repo hochladen (gleichnamige Datei überschreiben).
2. In `sw.js` die Zeile `const VERSION = "bass-tabs-v1";` hochzählen (v2, v3 …) und ebenfalls hochladen.
3. App auf dem iPad bei Internetverbindung öffnen, schließen und wieder öffnen – dann ist die neue Version aktiv.

## Wichtig zu den Daten
- Die Songs werden **nur in der App auf diesem iPad** gespeichert (nicht in GitHub, nicht in der Cloud).
- Die Home-Bildschirm-App hat einen eigenen Speicher, getrennt von Safari. Songs, die du in Safari anlegst, siehst du in der App nicht und umgekehrt – also immer über das Icon arbeiten.
- Regelmäßig **☰ Songs → Backup exportieren** (z. B. nach iCloud Drive sichern). Über **Backup importieren** kommen die Songs zurück, auch auf ein anderes Gerät.
