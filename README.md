# Vibe IPTV Player

**A fast, modern IPTV player for Android phones, tablets, and TV.**

![Version](https://img.shields.io/badge/version-1.4.3-76C3E4)
![Android](https://img.shields.io/badge/Android-7.0%2B-3DDC84)
![Platforms](https://img.shields.io/badge/platforms-Phone%20%C2%B7%20Tablet%20%C2%B7%20Android%20TV%20%C2%B7%20Fire%20TV-orange)

Vibe IPTV Player is a clean, remote-friendly player for your own IPTV subscriptions. Connect an **M3U** playlist or log in with the **Xtream Codes API** and browse Live TV, Movies, and Series with artwork, EPG, and a proper 10‑foot TV experience — or a touch-first layout on your phone.

> **Vibe is a player only.** It does **not** provide, host, or bundle any channels, streams, or media. You bring your own playlist from a provider you're subscribed to.

---

## ⬇️ Download

**[➡️ Download the latest APK](../../releases/latest)**

Grab the `.apk` file from the latest release and install it on your device (see below).

---

## 📲 Install

Because this app is distributed outside the Play Store, you'll need to allow installs from your browser or file manager the first time.

**On a phone or tablet**
1. Download the `.apk` from the [latest release](../../releases/latest).
2. Open it. If prompted, enable **Install unknown apps** for your browser/file manager.
3. Tap **Install**.

**On Android TV / Google TV / Fire TV**
1. Install a file/downloader app (e.g. *Downloader* or *Send Files to TV*).
2. Point it at the release `.apk` URL, or transfer the file from your phone.
3. Enable **Install unknown apps** for that app when prompted, then install.

**Verify your download (optional but recommended)**

Each release lists a SHA‑256 checksum. To confirm the file wasn't corrupted or tampered with:

```bash
# Windows (PowerShell)
Get-FileHash .\VibeIPTV.apk -Algorithm SHA256

# macOS / Linux
shasum -a 256 VibeIPTV.apk
```

The value should match the checksum in the release notes.

---

## ✨ Features

- **Live TV** with EPG (now/next + program guide) and category browsing
- **Movies & Series (VOD)** with rich detail pages: posters, synopsis, cast, ratings, trailers
- **Series support** — seasons, episodes, and resume-per-episode
- **Continue Watching** and **Favorites** across movies, series, and channels
- **Fast search** across your whole library, with search history
- **Offline downloads** of movies and episodes (with embedded subtitle tracks)
- **Chromecast** support
- **Android TV / Fire TV** 10‑foot layout with full D‑pad navigation, plus a touch‑first phone/tablet layout
- **QR pairing** — import a playlist from your phone to your TV without typing
- **Subtitles** with adjustable size, background, and opacity
- **Multiple playlist profiles** — switch between providers instantly
- **Light & dark themes** (mobile) and **English + Arabic** (full RTL)

---

## 📡 Supported playlists

- **M3U / M3U8** playlist URLs
- **Xtream Codes** login (server URL + username + password)
- **QR pairing** from the mobile app to the TV app over your local network

---

## 📱 Supported devices

- **Phones & tablets** — Android **7.0 (Nougat)** and newer
- **Android TV, Google TV, and Fire TV** — appears in the TV launcher with a leanback banner
- Works with or without Google Play Services (Chromecast is enabled only where available)

---

## 🔐 Permissions

Vibe requests only what it needs to play your streams and manage downloads:

| Permission | Why it's used |
|---|---|
| Internet / Network state | Load playlists and stream content |
| Wi‑Fi state | QR pairing between your phone and TV on the local network |
| Camera | Scan a QR code to import a playlist (optional) |
| Notifications | Show download progress |
| Foreground service | Keep downloads running in the background |
| Wake lock | Keep playback/downloads alive during use |

No account, sign‑up, ads, or trackers.

---

## 🛡️ Privacy & disclaimer

- Vibe stores your playlist details **only on your device** to connect to your provider.
- Vibe includes **no channels or media** and is not affiliated with any content provider. You are responsible for the legality of the playlists you add.

<!-- If you host your legal docs in this repo or on GitHub Pages, update these links. -->
See the **[Privacy Policy](privacy-policy.md)** and **[Terms of Use](terms-of-use.md)**.

---

## 🔄 Updates

This app updates manually (no Play Store auto‑update). **Watch** or **Star** this repository to be notified of new releases — then download the newer `.apk` and install it over your current version.

---

## ❓ Troubleshooting

- **"App not installed"** — a different build (e.g. a debug version) with the same name may already be installed. Uninstall it first, then install this one.
- **HTTP playlists** — many providers use plain `http://`. Vibe supports these; no extra setup is needed.
- **Nothing loads after login** — double‑check the server URL, username, and password, and confirm your subscription is active with your provider.

---

<sub>Vibe IPTV Player — a binary release. Bring your own playlist; enjoy your content on any screen.</sub>
