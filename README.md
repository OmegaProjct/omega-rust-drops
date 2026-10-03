# Omega Rust Drops

**Deutsch** · [English](#english)

Browser-Erweiterung für Firefox und Chrome. Sie schaut automatisch die passenden Rust-Streams auf Twitch und Kick (Beta) und sammelt deine Drops ein.

- Liest die aktuelle Kampagne von twitch.facepunch.com und deinen Fortschritt aus deinem Twitch-Inventar
- Öffnet den passenden Stream im Hintergrund, stumm und in 160p
- Überspringt Drops, die du schon hast, und wechselt zum nächsten live Streamer
- Löst fertige Drops auf deiner Twitch-Inventarseite ein
- Liest deinen Fortschritt auf Wunsch ganz ohne sichtbaren Tab
- Benachrichtigt dich bei neuer Kampagne, wenn ein Streamer mit fehlendem Drop live geht und wenn alles abgeholt ist
- Ein Klick führt zum passenden Streamer bzw. zu allen Rust-Streams mit Drops
- **Neu: Kick-Drops (Beta).** Auf Wunsch sammelt sie auch Rust-Drops auf Kick, ohne Stream-Tab im Hintergrund. Kick ist neu: Fehler sind möglich, Drops dort nicht garantiert.
- Deutsche und englische Oberfläche

## Installation

### Firefox
1. **[Neueste Version herunterladen](https://github.com/OmegaProjct/omega-rust-drops/releases/latest/download/omega-rust-drops-firefox.xpi)**
2. Firefox fragt nach, ob die Erweiterung installiert werden soll → **Hinzufügen**.
3. Updates kommen danach automatisch.

Die Datei ist von Mozilla signiert und bleibt dauerhaft installiert.

### Chrome / Brave / Edge

**Empfohlen: [Im Chrome Web Store installieren](https://chromewebstore.google.com/detail/omega-rust-drops/hgckfgbkanfneoghianbakhkojonmfpe)** → „Hinzufügen“. Updates kommen automatisch.

Neue Versionen erscheinen im Store erst, wenn Google sie geprüft hat. Das kann einige Tage dauern.

#### Neueste Version sofort, ohne Store

1. **[Zip herunterladen](https://github.com/OmegaProjct/omega-rust-drops/releases/latest/download/omega-rust-drops-chrome.zip)** (immer die neueste Version).
2. Die Zip-Datei **entpacken** (Rechtsklick → „Alle extrahieren“), am besten in einen festen Ordner, z. B. `Dokumente\Omega Rust Drops`. Den Ordner danach nicht löschen: Chrome lädt die Erweiterung von dort.
3. Hast du die Store-Version installiert, **entferne sie vorher**. Sonst laufen beide gleichzeitig.
4. In die Adresszeile eingeben: `chrome://extensions` (Edge: `edge://extensions`, Brave: `brave://extensions`).
5. Oben rechts den **Entwicklermodus** einschalten.
6. **„Entpackte Erweiterung laden“** klicken und den entpackten Ordner wählen, also den Ordner, in dem die Datei `manifest.json` liegt.
7. Über das Puzzle-Symbol in der Symbolleiste **Omega Rust Drops anheften**.

#### Updates ohne Store (Windows): Omega Updater

Im Ordner der Erweiterung liegt **„Omega Updater“**. Die Erweiterung zeigt dir einen Hinweis, sobald es eine neue Version gibt.

1. Doppelklick auf **„Omega Updater“**. Beim ersten Mal richtet er sich kurz ein; fragt Windows nach, ob die Datei ausgeführt werden soll, wähle **„Ausführen“**.
2. Im Fenster auf **„Jetzt aktualisieren“** klicken.
3. Die Erweiterung lädt sich innerhalb einer Minute selbst neu. Läuft gerade das Sammeln, geht es danach weiter. Einstellungen und Reihenfolge bleiben erhalten.

**Ganz automatisch:** Im Updater den Schalter **„Automatisch im Hintergrund aktualisieren“** einschalten. Dann prüft Windows alle 6 Stunden und nach der Anmeldung unsichtbar und spielt neue Versionen ein, ohne Fenster. Den Updater findest du danach auch im Startmenü unter „Omega Rust Drops Updater“. Bevor du den Ordner löschst, schalte den Schalter wieder aus.

**Ohne Updater (z. B. Mac/Linux):** Neue Zip herunterladen, in denselben Ordner entpacken und die alten Dateien ersetzen. Die Erweiterung lädt sich dann selbst neu.

**Zurück zum Store:** Die entpackte Version in `chrome://extensions` entfernen und die Store-Version installieren. Einstellungen und Reihenfolge stellst du dann einmal neu ein.

Fragt Chrome beim Start, ob Erweiterungen im Entwicklermodus deaktiviert werden sollen, wähle „Abbrechen“ bzw. schließe den Hinweis.

## Voraussetzungen
- Auf twitch.tv eingeloggt
- Twitch mit dem Facepunch-Konto verknüpft: https://twitch.facepunch.com/connect
- Für Kick (Beta): „Kick aktivieren“ in den Einstellungen, auf kick.com eingeloggt und verknüpft: https://kick.facepunch.com/connect

## Keine neuen Rust-Drops mehr verpassen?
- **Webseite:** **[rustdrops.omegaprojects.de](https://rustdrops.omegaprojects.de/)** zeigt die aktuelle Kampagne mit Countdown und allen Streamern. Im **[Archiv](https://rustdrops.omegaprojects.de/archiv/)** findest du alle bisherigen Kampagnen, mit Suche nach Drop, Streamer oder Kampagne.
- **Telegram:** Der Bot **[@OmegaRustDropBot](https://t.me/OmegaRustDropBot)** meldet dir neue Rust-Drop-Kampagnen, sobald Facepunch sie veröffentlicht, mit allen Drops, Streamern und Zeitfenstern.
- **Discord:** **[Omega Rust Drops Bot hinzufügen](https://discord.com/oauth2/authorize?client_id=1555124604706627624)**, dann im gewünschten Kanal `/setup` ausführen. Er postet neue Kampagnen, den Start und eine Erinnerung 24 Stunden vor dem Ende. Eine Rolle zum Erwähnen ist optional.

## Datenschutz
Keine Datensammlung, kein Tracking, alles bleibt im Browser. Details: [PRIVACY.md](PRIVACY.md)

## Unterstützen
Wenn dir die Erweiterung hilft: **[♥ Projekt unterstützen (PayPal)](https://www.paypal.com/paypalme/OmegaProjects)**

## Hinweis
Inoffiziell, nicht verbunden mit Facepunch Studios, Twitch oder Kick. Automatisches Schauen kann gegen die Nutzungsbedingungen von Twitch und Kick verstoßen. Die Nutzung erfolgt auf eigenes Risiko.

---

<a id="english"></a>

# Omega Rust Drops (English)

Browser extension for Firefox and Chrome. It automatically watches the right Rust streams on Twitch and Kick (beta) and collects your drops.

- Reads the current campaign from twitch.facepunch.com and your progress from your Twitch inventory
- Opens the right stream in the background, muted and at 160p
- Skips drops you already own and moves on to the next live streamer
- Claims finished drops on your Twitch inventory page
- Optionally reads your progress without any visible tab
- Notifies you about a new campaign, when a streamer with a missing drop goes live and when everything is claimed
- One click takes you to the right streamer or to all Rust streams with drops
- **New: Kick drops (beta).** If you want, it also collects Rust drops on Kick, in the background without a stream tab. Kick support is new: bugs are possible, drops there are not guaranteed.
- German and English interface

## Installation

### Firefox
1. **[Download the latest version](https://github.com/OmegaProjct/omega-rust-drops/releases/latest/download/omega-rust-drops-firefox.xpi)**
2. Firefox asks whether to install the extension → **Add**.
3. Updates arrive automatically.

The file is signed by Mozilla and stays installed permanently.

### Chrome / Brave / Edge

**Recommended: [Install from the Chrome Web Store](https://chromewebstore.google.com/detail/omega-rust-drops/hgckfgbkanfneoghianbakhkojonmfpe)** → "Add". Updates arrive automatically.

New versions appear in the store only after Google has reviewed them. This can take a few days.

#### Latest version right away, without the store

1. **[Download the zip](https://github.com/OmegaProjct/omega-rust-drops/releases/latest/download/omega-rust-drops-chrome.zip)** (always the latest version).
2. **Unzip** it (right click → "Extract All"), ideally into a permanent folder such as `Documents\Omega Rust Drops`. Do not delete the folder afterwards: Chrome loads the extension from there.
3. If you installed the store version, **remove it first**. Otherwise both run at the same time.
4. Type into the address bar: `chrome://extensions` (Edge: `edge://extensions`, Brave: `brave://extensions`).
5. Turn on **Developer mode** in the top right corner.
6. Click **"Load unpacked"** and pick the unzipped folder, i.e. the folder that contains `manifest.json`.
7. **Pin Omega Rust Drops** via the puzzle icon in the toolbar.

#### Updates without the store (Windows): Omega Updater

The extension folder contains **"Omega Updater"**. The extension shows a notice as soon as a new version is available.

1. Double-click **"Omega Updater"**. The first time it sets itself up briefly; if Windows asks whether to run the file, choose **"Run"**.
2. Click **"Update now"** in the window.
3. The extension reloads itself within a minute. If it is collecting, it carries on afterwards. Settings and order are kept.

**Fully automatic:** Turn on **"Update automatically in the background"** in the updater. Windows then checks every 6 hours and after sign-in, invisibly and without any window, and installs new versions. You also find the updater in the Start menu as "Omega Rust Drops Updater". Turn the switch off before deleting the folder.

**Without the updater (e.g. Mac/Linux):** Download the new zip, unzip it into the same folder and replace the old files. The extension then reloads itself.

**Back to the store:** Remove the unpacked version in `chrome://extensions` and install the store version. You set your settings and order once again.

If Chrome asks on startup whether to disable developer mode extensions, choose "Cancel" or close the message.

## Requirements
- Logged in on twitch.tv
- Twitch linked to your Facepunch account: https://twitch.facepunch.com/connect
- For Kick (beta): "Enable Kick" in the settings, logged in on kick.com and linked: https://kick.facepunch.com/connect

## Never miss new Rust drops again?
- **Website:** **[rustdrops.omegaprojects.de](https://rustdrops.omegaprojects.de/)** shows the current campaign with a countdown and every streamer. The **[archive](https://rustdrops.omegaprojects.de/archiv/)** lists all past campaigns, searchable by drop, streamer or campaign.
- **Telegram:** The bot **[@OmegaRustDropBot](https://t.me/OmegaRustDropBot)** tells you about new Rust drop campaigns as soon as Facepunch publishes them, with all drops, streamers and time windows.
- **Discord:** **[Add Omega Rust Drops Bot](https://discord.com/oauth2/authorize?client_id=1555124604706627624)**, then run `/setup` in the channel you want. It posts new campaigns, the start and a reminder 24 hours before the end. Mentioning a role is optional.

## Privacy
No data collection, no tracking, everything stays in the browser. Details: [PRIVACY.md](PRIVACY.md)

## Support
If the extension helps you: **[♥ Support the project (PayPal)](https://www.paypal.com/paypalme/OmegaProjects)**

## Note
Unofficial, not affiliated with Facepunch Studios, Twitch or Kick. Automated watching may violate the Twitch and Kick Terms of Service. Use at your own risk.
