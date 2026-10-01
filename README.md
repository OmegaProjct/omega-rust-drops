# Omega Rust Drops

**Deutsch** · [English](#english)

Browser-Erweiterung für Firefox und Chrome. Sie schaut automatisch die passenden Rust-Twitch-Streams und sammelt deine Drops ein.

- Liest die aktuelle Kampagne von twitch.facepunch.com und deinen Fortschritt aus deinem Twitch-Inventar
- Öffnet den passenden Stream im Hintergrund, stumm und in 160p
- Überspringt Drops, die du schon hast, und wechselt zum nächsten live Streamer
- Löst fertige Drops auf deiner Twitch-Inventarseite ein
- Liest deinen Fortschritt auf Wunsch ganz ohne sichtbaren Tab
- Benachrichtigt dich bei neuer Kampagne, wenn ein Streamer mit fehlendem Drop live geht und wenn alles abgeholt ist
- Ein Klick führt zum passenden Streamer bzw. zu allen Rust-Streams mit Drops
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

**Update ohne Store:** Neue Zip herunterladen, in denselben Ordner entpacken und die alten Dateien ersetzen. Dann in `chrome://extensions` bei Omega Rust Drops auf **↻ (Neu laden)** klicken. Einstellungen und Reihenfolge bleiben erhalten.

**Zurück zum Store:** Die entpackte Version in `chrome://extensions` entfernen und die Store-Version installieren. Einstellungen und Reihenfolge stellst du dann einmal neu ein.

Fragt Chrome beim Start, ob Erweiterungen im Entwicklermodus deaktiviert werden sollen, wähle „Abbrechen“ bzw. schließe den Hinweis.

## Voraussetzungen
- Auf twitch.tv eingeloggt
- Twitch mit dem Facepunch-Konto verknüpft: https://twitch.facepunch.com/connect

## Keine neuen Rust-Drops mehr verpassen?
Der Telegram-Bot **[@OmegaRustDropBot](https://t.me/OmegaRustDropBot)** meldet dir neue Rust-Drop-Kampagnen, sobald Facepunch sie veröffentlicht, mit allen Drops, Streamern und Zeitfenstern.

## Datenschutz
Keine Datensammlung, kein Tracking, alles bleibt im Browser. Details: [PRIVACY.md](PRIVACY.md)

## Unterstützen
Wenn dir die Erweiterung hilft: **[♥ Projekt unterstützen (PayPal)](https://www.paypal.com/paypalme/OmegaProjects)**

## Hinweis
Inoffiziell, nicht verbunden mit Facepunch Studios oder Twitch. Automatisches Schauen kann gegen die Twitch-Nutzungsbedingungen verstoßen. Die Nutzung erfolgt auf eigenes Risiko.

---

<a id="english"></a>

# Omega Rust Drops (English)

Browser extension for Firefox and Chrome. It automatically watches the right Rust Twitch streams and collects your drops.

- Reads the current campaign from twitch.facepunch.com and your progress from your Twitch inventory
- Opens the right stream in the background, muted and at 160p
- Skips drops you already own and moves on to the next live streamer
- Claims finished drops on your Twitch inventory page
- Optionally reads your progress without any visible tab
- Notifies you about a new campaign, when a streamer with a missing drop goes live and when everything is claimed
- One click takes you to the right streamer or to all Rust streams with drops
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

**Updating without the store:** Download the new zip, unzip it into the same folder and replace the old files. Then click **↻ (Reload)** on Omega Rust Drops in `chrome://extensions`. Settings and order are kept.

**Back to the store:** Remove the unpacked version in `chrome://extensions` and install the store version. You set your settings and order once again.

If Chrome asks on startup whether to disable developer mode extensions, choose "Cancel" or close the message.

## Requirements
- Logged in on twitch.tv
- Twitch linked to your Facepunch account: https://twitch.facepunch.com/connect

## Never miss new Rust drops again?
The Telegram bot **[@OmegaRustDropBot](https://t.me/OmegaRustDropBot)** tells you about new Rust drop campaigns as soon as Facepunch publishes them, with all drops, streamers and time windows.

## Privacy
No data collection, no tracking, everything stays in the browser. Details: [PRIVACY.md](PRIVACY.md)

## Support
If the extension helps you: **[♥ Support the project (PayPal)](https://www.paypal.com/paypalme/OmegaProjects)**

## Note
Unofficial, not affiliated with Facepunch Studios or Twitch. Automated watching may violate the Twitch Terms of Service. Use at your own risk.
