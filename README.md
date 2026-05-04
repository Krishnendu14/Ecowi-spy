# 📡 EcoWi-Spy: Multi-Modal Motion Detection

An experimental, web-based motion detection suite that transforms standard mobile hardware into a sophisticated sensor hub. No specialized equipment required—just a browser and a dream.

![License](https://img.shields.io/badge/License-MIT-green)
![Platform](https://img.shields.io/badge/Platform-Mobile--First-blue)
![Experimental](https://img.shields.io/badge/Status-Experimental-orange)

## 🌟 The Vision
Most motion detectors require PIR sensors or dedicated hardware. **EcoWi-Spy** pushes the boundaries of Web APIs to detect movement using physics and signal processing. Built entirely on a mobile device (Tecno Spark), this project proves that low-level computing and advanced sensing can happen anywhere.

---

## 🛠 Features (The Triad of Detection)

### 🔊 1. Doppler Sonar
Uses the **Web Audio API** to emit a near-ultrasonic 18.5kHz tone. By analyzing the frequency shifts in the reflected sound waves (the Doppler Effect), the system can detect movement in total darkness or even through thin fabric.
> **Physics:** Works like bat echolocation.

### 📶 2. EM-Signal (WIFI RSSI)
Monitors fluctuations in Wi-Fi signal strength. By polling network latency (RTT), the system detects "shadows" cast by human bodies moving between the device and the router.
> **Logic:** Your body is 70% water; you are a moving Wi-Fi obstacle.

### 📷 3. Camera Delta
Utilizes computer vision to compare pixel-by-pixel changes between video frames. Optimized for high sensitivity to detect even subtle shifts in the environment.

---

## 🚀 Quick Start

1. **Deploy:** Use GitHub Pages to host the `index.html`.
2. **Access:** Open the `https://` link in a modern mobile browser (Chrome recommended).
3. **Calibrate:**
   - Select a mode (Doppler is the most advanced).
   - Set the **Sensitivity** slider (5-7 is ideal).
   - Hit **ACTIVATE**.

> [!IMPORTANT]  
> **Secure Context Required:** This app requires HTTPS to access the Microphone and Camera. It will not work on standard `http://` or local `file://` links due to browser security policies.

---

## 📱 Mobile-First Development
This project was developed exclusively on a **Tecno Spark** mobile device. It emphasizes:
* **Optimization:** Low CPU overhead for real-time signal processing.
* **Visuals:** High-refresh radar UI and real-time signal waveforms.
* **Architecture:** Understanding technology from the ground up rather than relying on pre-built libraries.

---

## ⚠️ Known Limitations
* **Browser Permissions:** Some mobile browsers may block the ultrasonic tone or camera access. 
* **Hardware Variation:** Microphone sensitivity varies by device, which may affect Doppler accuracy.

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
*Created by [Krishnendu](https://github.com/krishnendu14) — Exploring the intersection of physics and web technology.*
