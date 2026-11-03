# Enigma2Webif

> Android app to control your Enigma2 satellite receiver remotely — a modern mobile client for OpenWebif.

![Platform](https://img.shields.io/badge/Platform-Android-green)
![Framework](https://img.shields.io/badge/.NET%20MAUI-10.0-blueviolet)
![License](https://img.shields.io/badge/License-GPLv3-blue)
![Version](https://img.shields.io/badge/Version-1.2.0-orange)

<p align="center">
  <a href="https://ko-fi.com/lululla">
    <img src="https://img.shields.io/badge/_-Donate-red.svg?logo=githubsponsors&labelColor=555555&style=for-the-badge" alt="Donate via Ko-fi">
  </a>
  <a href="https://paypal.me/belfagor2005">
    <img src="https://img.shields.io/badge/_-Donate-green.svg?logo=githubsponsors&labelColor=555555&style=for-the-badge" alt="Donate via PayPal">
  </a>
</p>

---

## 📱 About

**Enigma2Webif** is a native Android application that brings the power of [OpenWebif](https://github.com/oe-alliance/OpenWebif) to your smartphone. Control your Enigma2 decoder (Uclan, Vu+, Zgemma, Octagon, Dreambox, and many more) with a modern, clean and fast interface.

Built with **.NET MAUI 10** for maximum performance and native look-and-feel.

---

## ✨ Features

### 🎛️ Control
- **Multi-Box** — Save multiple receiver profiles with encrypted passwords (SecureStorage)
- **Full Virtual Remote** — Arrow keys, OK, Menu, Info, EPG, Exit, colored buttons, numbers, playback, TV/Radio/Audio/Video. Uses correct RC codes (Record=167, Radio=385, etc.)
- **Remote Configurator** — Customize Short/Long press actions for every key (e.g., Long STOP to open PVR). Supports `type=long` API.
- **Text Input** — Send free text to the box (useful for YouTube/Netflix searches).
- **Power Menu** — Standby, Deep Standby, Reboot, Restart Enigma2, Wake Up, **Wake on LAN**.
- **Power Timer** — Schedule box power on/off.
- **HDMI-CEC (Skip TV)** — Power on the box without turning on the TV.
- **Sleep Timer** — Programmed shutdown with configurable delay (native API).
- **OSD Messages** — Send popup messages to the TV screen.
- **Advanced Signal Finder** — Live JSON graph (SNR/AGC/BER) + Audio Metal Detector beep.
- **Parental Control** — PIN-protected channels & bouquets.

### 📺 Content
- **Bouquets & Channels** — Lazy Loading, Picon support, EPG Now, and a **Now/Next guide** per bouquet.
- **EPG Guide** — Full guide with Event Details Page, "Find Similar Programs", and REC button.
- **Export** — Export bouquets as M3U or XSPF via Swipe.
- **Audio & Subtitles** — Real-time track switching. Subservices support (multistream).
- **Global Search** — Search channels and programs simultaneously.
- **Timers** — Advanced creation and editing (justplay, tags, target folder, always zap, allow duplicate).

### 🛠️ Tools
- **Screenshot** — Capture the box screen in real time.
- **Telnet** — Direct terminal with quick commands.
- **FTP** — Browse, download, upload files.
- **Box Info** — Firmware, kernel, chipset, tuners, HDD, network, RAM.

### 🎬 Streaming
- **Live TV** — Watch the current channel via VLC (transcoded stream on port 8001).
- **Advanced Recordings** — Full Movie List across all locations, Rename, Delete, Move, Copy, and **Tag management**.

### 🌍 Experience
- **5 Languages** — Italian, English, German, French, Spanish (live switch).
- **Daily Support Prompt** — A daily, dismissible prompt asking for a coffee donation (can be permanently disabled).
- **Dark Theme** — Forced dark mode with modern gradient UI.
- **Integrated Guide** — 25+ sections explaining every feature.

---

## 🚀 Installation

1. Download the latest APK from the **Releases** section.
2. Enable **Install from unknown sources**.
3. Open the APK and install.
4. Launch the app and configure your box in **Settings**.

---

## 📖 User Guide (Highlights)

- **Remote Control**: Long-press keys (like STOP or REC) to open advanced menus (configured via Remote Settings).
- **Signal Finder**: Activate the "Beep Audio" toggle to align your dish like a metal detector. The frequency increases with the SNR.
- **Advanced Recordings**: Swipe left on a recording to Copy, Add Tag, or Remove Tag. Manage recording folders (Locations) via the top menu.
- **Now on TV**: Click the 🕒 icon in the Channels list to see what's playing on all channels in that bouquet.
- **Power Timer & CEC**: Schedule wake-ups or use "Power on without TV" to avoid waking the TV via HDMI-CEC.

---

## 🖥️ Supported Receivers

Any Enigma2 receiver with **OpenWebif 1.5+** installed (Uclan, Vu+, Zgemma, Octagon, Dreambox, Gigablue, Edision...).
**Images tested**: OpenATV, OpenPLi, OpenBH, OpenVision, OpenEight, OpenSPA.

---

## ☕ Support Development

If you find this app useful, consider supporting the development:

👉 [PayPal — belfagor2005](https://paypal.me/belfagor2005)
👉 [Ko-Fi — belfagor2005](https://ko-fi.com/lululla)

---

## 📜 License

GNU General Public License v3.0.

---

*Made with ❤️ for the Enigma2 community*
