# Enigma2Webif

> Android app to control your Enigma2 satellite receiver remotely — a modern mobile client for OpenWebif.

![Platform](https://img.shields.io/badge/Platform-Android-green)
![Framework](https://img.shields.io/badge/.NET%20MAUI-10.0-blueviolet)
![License](https://img.shields.io/badge/License-GPLv3-blue)
![Version](https://img.shields.io/badge/Version-1.5.0-orange)

<p align="center">
  <a href="https://ko-fi.com/lululla">
    <img src="https://img.shields.io/badge/_-Donate-red.svg?logo=githubsponsors&labelColor=555555&style=for-the-badge" alt="Donate via Ko-fi">
  </a>
  <a href="https://paypal.me/belfagor2005">
    <img src="https://img.shields.io/badge/_-Donate-green.svg?logo=githubsponsors&labelColor=555555&style=for-the-badge" alt="Donate via PayPal">
  </a>
</p>

---

## 📸 Screenshots

### 🏠 Home & Navigation
| Home (1) | Home (2) | Home (3) |
|:---:|:---:|:---:|
| <img src="https://raw.githubusercontent.com/Belfagor2005/Enigma2Webif/main/Screen/home1.png" height="380"/> | <img src="https://raw.githubusercontent.com/Belfagor2005/Enigma2Webif/main/Screen/home2.png" height="380"/> | <img src="https://raw.githubusercontent.com/Belfagor2005/Enigma2Webif/main/Screen/home3.png" height="380"/> |

### 📺 Content & EPG
| Bouquet | Bouquet Editor | EPG Grid |
|:---:|:---:|:---:|
| <img src="https://raw.githubusercontent.com/Belfagor2005/Enigma2Webif/main/Screen/bouquet.png" height="380"/> | <img src="https://raw.githubusercontent.com/Belfagor2005/Enigma2Webif/main/Screen/bouquet_edit.png" height="380"/> | <img src="https://raw.githubusercontent.com/Belfagor2005/Enigma2Webif/main/Screen/epggrid.png" height="380"/> |

### 🎛️ Control & Remote
| Remote | Live TV | Player Integrato |
|:---:|:---:|:---:|
| <img src="https://raw.githubusercontent.com/Belfagor2005/Enigma2Webif/main/Screen/remote.png" height="380"/> | <img src="https://raw.githubusercontent.com/Belfagor2005/Enigma2Webif/main/Screen/livetv1.png" height="380"/> | <img src="https://raw.githubusercontent.com/Belfagor2005/Enigma2Webif/main/Screen/livetv2.png" height="380"/> |

| Timers | Notifiche | Registrazioni |
|:---:|:---:|:---:|
| <img src="https://raw.githubusercontent.com/Belfagor2005/Enigma2Webif/main/Screen/timers1.png" height="380"/> | <img src="https://raw.githubusercontent.com/Belfagor2005/Enigma2Webif/main/Screen/notification.png" height="380"/> | <img src="https://raw.githubusercontent.com/Belfagor2005/Enigma2Webif/main/Screen/recordings.png" height="380"/> |

### 🛠️ Tools & Info
| Screenshot | Telnet | FTP |
|:---:|:---:|:---:|
| <img src="https://raw.githubusercontent.com/Belfagor2005/Enigma2Webif/main/Screen/screenshot.png" height="380"/> | <img src="https://raw.githubusercontent.com/Belfagor2005/Enigma2Webif/main/Screen/telnet.png" height="380"/> | <img src="https://raw.githubusercontent.com/Belfagor2005/Enigma2Webif/main/Screen/ftp.png" height="380"/> |

| Settings (Tema + Backup) | Widget Home | Ricerca Vocale |
|:---:|:---:|:---:|
| <img src="https://raw.githubusercontent.com/Belfagor2005/Enigma2Webif/main/Screen/settings.png" height="380"/> | <img src="https://raw.githubusercontent.com/Belfagor2005/Enigma2Webif/main/Screen/widget.png" height="380"/> | <img src="https://raw.githubusercontent.com/Belfagor2005/Enigma2Webif/main/Screen/voicesearch.png" height="380"/> |

---

## 📱 About

**Enigma2Webif** is a native Android application that brings the power of [OpenWebif](https://github.com/oe-alliance/OpenWebif) to your smartphone. Control your Enigma2 decoder (Uclan, Vu+, Zgemma, Octagon, Dreambox, and many more) with a modern, clean and fast interface.

Built with **.NET MAUI 10** for maximum performance and native look-and-feel.

---

## ✨ Features (v1.5.0)

### 🎬 Media & Streaming
- **Built-in Video Player** — Watch channels directly in the app, no more VLC required. Includes **Picture-in-Picture** support (press Home and the video shrinks to a floating window).
- **Local Download** — Download recordings from the box HDD to your phone via FTP, with a live progress bar.
- **Live TV** — Transcoding profiles (Low/Medium/High/HD), Subservices support.
- **Media Player** — Browse HDD via FTP, play on TV (`zap`) or on phone.
- **Unified Recordings** — A single page with full movie list, tags, locations, rename, move, copy, delete, download.
- **Audio & Subtitles** — Real-time track switching.

### 🎛️ Control
- **Advanced Remote** — Physical layout, short/long press, haptic feedback (vibration).
- **Button Setup** — Assign native Enigma2 actions to hardware keys.
- **Power Menu** — Standby, Deep Standby, Reboot, Restart, Wake Up, WOL, Power Timer, HDMI-CEC.
- **Sleep Timer** — Programmed shutdown.
- **OSD Messages** — Popup to TV.
- **Signal Finder** — SNR/AGC/BER graph + audio beep.
- **Parental Control** — PIN-protected channels.

### 📺 Content & Editing
- **EPG Grid (Palimpsest)** — 2D guide with JSON cache (5 min).
- **Plugin Manager** — FTP scan + AutoTimer and EPGRefresh editors.
- **Bouquet Editor** — Create, rename, delete bouquets. Move, rename, add, remove channels. Add markers.
- **Global Search** — Channels + Programs in parallel. **Voice search** via native Android microphone.
- **Export** — M3U / XSPF.

### ⏰ Automation
- **Timer Notifications** — Get a push notification 2 minutes before a timer starts.
- **Home Assistant Webhook** — Send events to your domotics system when you change channel or start a recording.
- **Widget Home Screen** — Shows current channel on your home screen. Tap to open the app.

### 🛠️ Tools & System
- **Backup & Restore** — Export/Import all settings (boxes, remote keys, parental list) to a JSON file.
- **Local Cache (SQLite)** — Channels and EPG saved locally. App opens instantly even when the box is offline.
- **Screenshot** — Modes (All/Video/OSD), formats (JPG/PNG), resolutions.
- **Telnet, FTP, Box Info, System Info, Plugin Manager**.
- **Crash Reporting** — Powered by Sentry.

### 🎨 Experience
- **Light / Dark Theme** — Follow system or manual choice.
- **Haptic Feedback** — Remote keys vibrate on press.
- **Skeleton Loading** — Modern loading placeholders.
- **Empty States** — Friendly messages when lists are empty.
- **Toast Notifications** — Non-blocking popups.
- **5 Languages** — IT, EN, DE, FR, ES.
- **Integrated Guide** — 43 sections covering every feature.

---

## 🚀 Installation

1. Download the latest APK from the **Releases** section.
2. Enable **Install from unknown sources**.
3. Open the APK and install.
4. Launch the app and configure your box in **Settings**.

---

## 🖥️ Supported Receivers

Any Enigma2 receiver with **OpenWebif 1.5+** installed (Uclan, Vu+, Zgemma, Octagon, Dreambox, Gigablue, Edision...).
**Images tested**: OpenATV, OpenPLi, OpenBH, OpenVision, OpenEight, OpenSPA.

---

## ☕ Support Development

If you find this app useful, consider supporting the development:

👉 [PayPal — belfagor2005](https://paypal.me/belfagor2005)
👉 [Ko-Fi — lululla](https://ko-fi.com/lululla)

---

## 📜 License

GNU General Public License v3.0.

---

*Made with ❤️ for the Enigma2 community*
