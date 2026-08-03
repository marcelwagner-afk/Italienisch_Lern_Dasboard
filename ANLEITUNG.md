# Italiano-App auf dein iPhone bringen

Die App besteht aus 6 Dateien (in diesem ZIP). Du legst sie einmalig kostenlos bei GitHub ins Netz — danach kannst du sie auf dem iPhone wie eine echte App installieren. Dauert insgesamt ca. 10 Minuten.

## Teil 1: Veröffentlichen mit GitHub Pages (einmalig, am Computer)

1. **GitHub-Konto anlegen** (falls noch keins vorhanden): Gehe auf https://github.com/signup und registriere dich kostenlos mit deiner E-Mail-Adresse.

2. **Neues Repository erstellen**: Nach dem Anmelden oben rechts auf das **+** klicken → **New repository**.
   - Repository name: `italiano` (oder ein Name deiner Wahl, klein geschrieben)
   - Sichtbarkeit: **Public** (nötig für kostenloses GitHub Pages)
   - Auf **Create repository** klicken.

3. **Dateien hochladen**: Auf der nächsten Seite auf den Link **„uploading an existing file"** klicken. Dann alle 6 Dateien aus dem entpackten ZIP in das Fenster ziehen:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-180.png`
   - `icon-192.png`
   - `icon-512.png`

   Wichtig: die Dateien selbst hochladen, nicht den Ordner. Unten auf **Commit changes** klicken.

4. **GitHub Pages einschalten**: Oben im Repository auf **Settings** → links im Menü auf **Pages**.
   - Unter „Build and deployment" bei **Source**: „Deploy from a branch" auswählen.
   - Bei **Branch**: `main` und `/ (root)` auswählen → **Save**.

5. **1–2 Minuten warten**, dann die Pages-Seite neu laden. Oben erscheint deine Adresse:

   `https://DEIN-BENUTZERNAME.github.io/italiano/`

   Diese Adresse einmal am Computer öffnen und prüfen, ob das Dashboard erscheint.

## Teil 2: Als App auf dem iPhone installieren

1. Öffne die Adresse in **Safari** auf dem iPhone (Adresse z. B. per Nachricht an dich selbst schicken).
2. Tippe unten auf das **Teilen-Symbol** (Quadrat mit Pfeil nach oben).
3. Wähle **„Zum Home-Bildschirm"** und tippe auf **Hinzufügen**.

Fertig! Auf dem Home-Bildschirm liegt jetzt „Italiano" mit eigenem Icon. Die App startet im Vollbild, funktioniert nach dem ersten Öffnen auch offline (z. B. in der Halle ohne Empfang), und dein Lernfortschritt wird auf dem iPhone gespeichert.

## Später etwas ändern

Wenn ich dir mal eine neue Version baue (z. B. mit mehr Vokabeln): einfach im Repository die alte `index.html` durch die neue ersetzen (Datei anklicken → Stift-Symbol bzw. neu hochladen) — die App auf dem iPhone holt sich die Änderung beim nächsten Öffnen mit Internetverbindung automatisch.

## Hinweise

- Die Seite ist öffentlich erreichbar, aber nur für Leute, die die Adresse kennen. Es sind keine persönlichen Daten enthalten — nur Vokabeln.
- Der Lernfortschritt wird nur lokal auf dem jeweiligen Gerät gespeichert (iPhone und Computer haben also getrennte Fortschritte).
