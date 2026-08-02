<div align="center">
<img width="1024" height="225" alt="firmwarehub" src="https://github.com/user-attachments/assets/7a5ee7c2-c3c8-4c6e-85a7-e2a72228b346" />

<!-- Badges -->

<a href="https://github.com/cifertech/FirmwareHub" title="Go to GitHub repo"><img src="https://img.shields.io/static/v1?label=cifertech&message=FirmwareHub&color=orange&logo=github" alt="cifertech - FirmwareHub"></a>
<a href="https://github.com/cifertech/FirmwareHub"><img src="https://img.shields.io/github/stars/cifertech/FirmwareHub?style=social" alt="stars - FirmwareHub"></a>
<a href="https://github.com/cifertech/FirmwareHub"><img src="https://img.shields.io/github/forks/cifertech/FirmwareHub?style=social" alt="forks - FirmwareHub"></a>
<a href="https://github.com/cifertech/FirmwareHub/blob/main/LICENSE"><img src="https://img.shields.io/github/license/cifertech/FirmwareHub?color=orange" alt="license - FirmwareHub"></a>

<h4>
    <a href="https://twitter.com/techcifer">TWITTER</a>
  <span> · </span>
    <a href="https://www.instagram.com/cifertech/">INSTAGRAM</a>
  <span> · </span>
    <a href="https://www.youtube.com/c/techcifer">YOUTUBE</a>
  <span> · </span>
    <a href="https://cifertech.net/">WEBSITE</a>
  </h4>
</div>
<br />

# 🚀 FirmwareHub  
### A Modern Web Flasher for ESP32 Projects  
**Flash, update, and manage firmware for all CiferTech devices, right from your browser.**  
Works with: **RF-Clown**, **ESP32-DIV**, **nRFBox**, and any ESP32/ESP8266 board.


## ✨ Features
- **One-click flashing** for `.bin` firmware (local or remote)  
- **WebSerial-based flashing** (Chrome/Edge, no software needed)  
- **GitHub Releases integration**  
  - Auto-fetch `.bin` assets  
  - Flash latest versions instantly  
  - Copy OTA URLs  
- **Device info panel**  
  - Chip family, flash size, MAC address  
- **Serial console** (read & send commands)  
- **Flash history** stored locally  
- **Drop-zone UI**, progress bar, dark CiferTech theme  



## 🧠 How It Works
FirmwareHub uses **WebSerial + esptool.js** to flash firmware directly from your browser.  
For remote updates, it reads `.bin` files from **GitHub Releases** of your repositories.



## 🔧 Usage
1. Open the [web app](https://cifertech.github.io/FirmwareHub/)
2. Connect your ESP32 board  
3. Load local firmware or pick a release from GitHub  
4. Click **Flash**  

> ⚠️ Use Chrome/Edge. WebSerial requires HTTPS when hosted online.



## 🤝 Contribute

Want to help make FirmwareHub better?

- Submit bug reports  
- Suggest new features  
- Improve documentation  
- Contribute code or UI elements  
- Star ⭐ and share the project  

Every contribution helps. Thank you! ❤️
