
<img width="1408" height="768" alt="1786797042390" src="https://github.com/user-attachments/assets/3eefde98-3f3b-46ed-8a95-1567ad8fe48e" />


  <h1>🦊 OrangeFox Recovery Project</h1>
  <strong>Custom Recovery for POCO F4 GT (ingres)</strong>
  
  <br>

  [![Version](https://img.shields.io/badge/Version-R12.0_1-orange.svg)](https://orangefox.download)
  [![Status](https://img.shields.io/badge/Status-Unofficial-red.svg)](#)
  [![Android](https://img.shields.io/badge/Android-15%20%7C%2016%20%7C%2017-green.svg)](#)
  
</div>

---

## 📱 Device Specifications

| Feature | Specification |
| :--- | :--- |
| **Device** | POCO F4 GT / Redmi K50 Gaming |
| **Codename** | `ingres` |
| **Chipset** | Qualcomm SM8450 Snapdragon 8 Gen 1 (4 nm) |
| **Architecture** | ARM64 |
| **Maintainer** | [Nama/Username GitHub Kamu] |

---

## ✨ Features

* Synced with the latest OrangeFox source changes
* Support for Decryption (Android 12/13/14)
* Support for OTA updates (MIUI/HyperOS & Custom ROMs)
* Built-in Magisk patching
* Password protection
* Fully open-source and highly customizable UI

---

## 🛠️ Installation Guide

### Prerequisites
* Unlocked Bootloader
* ADB and Fastboot installed on your PC
* Download the latest `recovery.img` or `.zip` release

### Flashing via Fastboot
1. Reboot your device into Fastboot mode (Hold `Power` + `Volume Down`).
2. Connect the device to your PC.
3. Open a terminal/command prompt and run the following commands:
   ```bash
   fastboot flash recovery_ab recovery.img
   fastboot reboot recovery
