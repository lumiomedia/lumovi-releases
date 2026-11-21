# Lumovi

Installers for **Lumovi**, a media player for your own libraries, sources and Live TV on Mac, Android, Android TV and, through the browser, iPhone.

**Website:** https://lumovi.se

> This repository only hosts the installation files. Lumovi is not open source, and the app's source code is not published here.

## Download

Always the latest version:

| Platform | Download |
|---|---|
| **Mac** (Apple Silicon) | [Lumovi-mac.dmg](https://github.com/lumiomedia/lumovi-releases/releases/latest/download/Lumovi-mac.dmg) |
| **Android** phones, tablets and **Android TV** (Android 6 and later) | [Lumovi.apk](https://github.com/lumiomedia/lumovi-releases/releases/latest/download/Lumovi.apk) |

Older versions and release notes are under [Releases](https://github.com/lumiomedia/lumovi-releases/releases).

## Install

### Mac
1. Open `Lumovi-mac.dmg` and drag **Lumovi** to **Applications**.
2. Open Lumovi. If macOS says it can't verify the developer, go to **System Settings → Privacy & Security** and click **Open Anyway**.
3. Follow the welcome guide.

After that, Lumovi updates itself from inside the app.

### Android and Android TV
1. Download `Lumovi.apk` on the device. On a TV, use a downloader app or send the file from your phone.
2. Allow installs from that app when Android asks, then tap **Install**.
3. Open Lumovi. On a TV it starts in TV mode automatically.

One APK covers phones, tablets and TVs. Lumovi updates itself from inside the app.

### iPhone
On your Mac or TV, open **Settings → Paired phones**. Scan the QR code with the iPhone camera, open the link in Safari and choose **Share → Add to Home Screen**.

## Free and supporting

Lumovi is free, and everything is unlocked for the first 14 days. After that, a few extras are for [supporters on Patreon](https://www.patreon.com/Lumovi). Playback is always free. See [lumovi.se/pricing](https://lumovi.se/pricing).

## Verify a download

Each release lists SHA-256 checksums in its notes. To check a file on Mac:

```
shasum -a 256 Lumovi-mac.dmg
```

## Help

Guides and FAQ: https://lumovi.se/wiki

Bundled open-source components and their licences are listed in the app under **Settings → Advanced → Licenses**.
