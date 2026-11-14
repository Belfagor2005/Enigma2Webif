# Enigma2Webif

> Android app to control your Enigma2 satellite receiver remotely — a modern mobile client for OpenWebif.

![Platform](https://img.shields.io/badge/Platform-Android%20%7C%20Android%20TV-green)
![Framework](https://img.shields.io/badge/.NET%20MAUI-10.0-blueviolet)
![License](https://img.shields.io/badge/License-GPLv3-blue)
![Version](https://img.shields.io/badge/Version-1.8.0-orange)

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

**Enigma2Webif** is a native Android application that brings the power of [OpenWebif](https://github.com/oe-alliance/OpenWebif) to your smartphone and Android TV. 

Control your Enigma2 decoder (Uclan, Vu+, Zgemma, Octagon, Dreambox, and many more) with a modern, clean and fast interface. Built with **.NET MAUI 10** for maximum performance and native look-and-feel.

---

## ✨ EVERYTHING THE APP CAN DO (v1.8.0)

Here is the complete, exhaustive list of all features included in Enigma2Webif:

### 🌐 Box & Connection Management
- **Multi-Box Support**: Configure and switch between multiple decoders.
- **Secure Storage**: Passwords are saved securely using Android SecureStorage.
- **Port Configuration**: Customize HTTP, Telnet, and FTP ports for each box.
- **Connection Status**: Live banner showing online/offline status and current channel.
- **Backup & Restore**: Export/Import all profiles, remote mappings, and parental settings to a JSON file.
- **In-App Updates**: Automatic check for new GitHub releases on startup and manual check in Settings.
- **Maintenance Dashboard**: Real-time monitoring of RAM, Disk, and CPU Temperature with Gauge animations. Includes "RAM Boost" (drop_caches), GUI Restart, Box Reboot, and Standby actions directly from the app (with Telnet/HTTP fallback).

### 📺 Channels, Bouquets & EPG
- **Bouquet List**: Browse all your satellite and IPTV bouquets with lazy loading.
- **Channel List**: View channels with Picons (logos), EPG Now, and active timer indicators.
- **Lightning Search**: A fixed search bar at the top of the Channels list to instantly filter channels without lagging the UI (debounced).
- **Edit Mode**: Toggle Edit Mode to Reorder (Up/Down), Rename, or Delete bouquets and channels directly from the app.
- **Bouquet Editor**: Create/Delete bouquets, add markers, move channels between folders.
- **EPG Grid (Palimpsest)**: A 2D scrollable TV guide spanning 12 hours, with synchronized horizontal and vertical scrolling.
- **EPG Details**: View full program descriptions, live progress bars, and start times.
- **Find Similar**: Discover similar programs based on the current event.
- **Global Search**: Search for both Channels and Programs simultaneously.
- **Advanced Search Filters**: Filter program results by Movies, Sports, or News.
- **Voice Search**: Use your phone's microphone to search for channels (e.g., say "Rai 1").
- **Picons Support**: Automatically loads channel logos from the box.

### 🎬 Streaming, Media & Recordings
- **Built-in Video Player**: Watch TV directly in the app with Transcoding profiles (Low/Medium/High/HD).
- **Picture-in-Picture (PiP)**: Shrink the player into a floating window when you press the Home button.
- **Mini Player in Home**: A small, persistent video widget on the Home screen to keep an eye on the current channel while browsing the app.
- **Listen Mode (Headphones)**: Route the TV audio directly to your phone's headphones (or Bluetooth) without muting the TV sound for others in the room.
- **Background Media Session**: Native Android Play/Pause/Stop controls in the notification tray while playing in the background.
- **Media Player Watchdog**: If the app is closed during playback, it asks to restore the TV channel on next launch.
- **Audio & Subtitles**: Change audio tracks and subtitles in real-time during Live TV.
- **Subservices**: Support for multistream channels (alternative commentators/feeds).
- **Media Player (HDD)**: Browse your box's hard drive via FTP and play files directly on the TV or on your phone.
- **Recordings Manager**: View, play, rename, move, copy, or delete recordings on your box.
- **Multi-Select**: Long-press to select multiple recordings and delete or download them in batch.
- **Download to Phone**: Download `.ts` recordings to your phone with a live progress bar.
- **Export M3U**: Save IPTV bouquets as `.m3u` files and share them via the native Android share menu.

### 🎛️ Remote, Power & Automation
- **Advanced Virtual Remote**: Full physical layout with Haptic Feedback (vibration) and Short/Long press support.
- **Button Setup**: Remap your hardware color keys (Red, Green, Yellow, Blue) with over 20 Enigma2 native actions.
- **Custom RC Mapping**: Reassign what code is sent for 40+ remote buttons.
- **Power Menu**: Standby, Deep Standby, Reboot, Restart GUI, Wake Up, and Wake-on-LAN (WOL).
- **Power Timers**: Schedule when the box should turn on or off.
- **Sleep Timer**: Set a countdown to automatically put the box in standby.
- **OSD Messages**: Send popup messages directly to your TV screen (Info, Warning, Error).
- **OSD Questions**: Send a Yes/No question to the TV and get the answer on your phone.
- **Signal Finder**: A beautiful **Circular Gauge** (3 concentric rings for SNR, AGC, BER) with smooth 60fps animations. Includes the OpenATV AGC estimation fix and a real-time audio beeper. SNR/AGC bars are also shown directly in the Live TV page.

### ⏰ Timers & Advanced Tools
- **Manual Timer Creation**: Create recordings from scratch (like the Webif browser). Search for a channel, set dates, times, destination folder, and advanced options (Just Play, Always Zap, PiP Zap).
- **EPG Timer Creation**: Create a timer with one tap directly from the EPG.
- **Timer Notifications**: Push notifications 2 minutes before a timer starts and 1 minute before it ends/fails.
- **Softcam Integration**: Quick access to open OSCam and CCcam web interfaces (with editable ports).
- **Telnet Client**: Auto-login terminal with quick command buttons (reboot, df -h, free, etc.).
- **FTP Client**: Browse the box file system, view text files, and navigate directories.
- **Screenshot Tool**: Capture your TV screen. Supports All/Video/OSD modes, JPG/PNG formats, and Native/UHD/WQHD resolutions. Saves via Android Share menu.
- **System Info**: View current PID streams, Satellite configurations, and tuner live status.
- **Box Info**: Detailed firmware, kernel, CPU, RAM, network, and HDD information.
- **Plugin Manager**: Scan installed plugins via FTP and edit AutoTimer and EPGRefresh configurations.

### 📱 Integrations & UI
- **Customizable Home**: Hide/Show, reorder, and restore default tiles. Your layout is saved locally.
- **Parental Control**: PIN-protect specific channels and bouquets.
- **Home Assistant Webhook**: Send JSON events to your smart home when you change channels or start recordings.
- **Home Screen Widget**: Displays current channel and EPG description. Tap to open the app.
- **Android TV Support**: Officially compatible with Android TV and Leanback (remote and mouse friendly).
- **Responsive Layout**: Home grid automatically scales to 3 or 4 columns on Tablets and Foldables.
- **Light / Dark Theme**: Follow system settings or choose manually.
- **5 Languages**: 100% translated in Italian, English, German, French, and Spanish (no hardcoded strings).
- **Integrated Guide**: A fully translated 44-section manual explaining every single feature.
- **Crash Reporting**: Sentry integrated (Release only) for stability tracking.

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
| Remote | Live TV |
|:---:|:---:|
| <img src="https://raw.githubusercontent.com/Belfagor2005/Enigma2Webif/main/Screen/remote.png" height="380"/> | <img src="https://raw.githubusercontent.com/Belfagor2005/Enigma2Webif/main/Screen/livetv1.png" height="380"/> |

| Timers | Registrazioni |
|:---:|:---:|
| <img src="https://raw.githubusercontent.com/Belfagor2005/Enigma2Webif/main/Screen/timers1.png" height="380"/> | <img src="https://raw.githubusercontent.com/Belfagor2005/Enigma2Webif/main/Screen/recordings.png" height="380"/> |

### 🛠️ Tools & Info
| Screenshot | Telnet | FTP |
|:---:|:---:|:---:|
| <img src="https://raw.githubusercontent.com/Belfagor2005/Enigma2Webif/main/Screen/screenshot.png" height="380"/> | <img src="https://raw.githubusercontent.com/Belfagor2005/Enigma2Webif/main/Screen/telnet.png" height="380"/> | <img src="https://raw.githubusercontent.com/Belfagor2005/Enigma2Webif/main/Screen/ftp.png" height="380"/> |

| Settings (Tema + Backup) | 
|:---:|
| <img src="https://raw.githubusercontent.com/Belfagor2005/Enigma2Webif/main/Screen/settings.png" height="380"/> |

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
