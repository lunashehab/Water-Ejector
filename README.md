# Water In My Speaker 💧🔊

[![Website Status](https://img.shields.io/website?url=https%3A%2F%2Fwaterinmyspeaker.com&style=flat-square&label=Live%20Status&logo=google-chrome&logoColor=white&color=success)](https://waterinmyspeaker.com)
[![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)](LICENSE)
[![Size](https://img.shields.io/github/repo-size/lunashehab/Water-Ejector?style=flat-square&label=Code%20Size&color=orange)]()

**The Professional Emergency Water Ejection Utility.**
*Save your phone from water damage using precision audio frequencies.*

[🔴 **Launch Live App**](https://waterinmyspeaker.com)

---

## 🚨 The Problem
Modern smartphones are water-resistant, but their speaker grills are not. When water gets trapped inside the mesh, it muffles audio and can cause long-term corrosion. Traditional methods (shaking, rice) often fail to remove water trapped deep inside the acoustic chamber.

## 🛠️ The Solution
**WaterInMySpeaker** utilizes the browser's native `AudioContext` API to generate a specific **165Hz Sawtooth Wave**. This frequency creates a high-pressure air displacement event that physically pushes water droplets out of the speaker grill without damaging the hardware.

## ✨ Key Features
* **🌊 One-Tap Ejection:** Instantly generates the calibrated 165Hz "Eject" tone.
* **🔊 Stereo Diagnostics:** Independent Left/Right channel testing to identify specific side damage.
* **🎚️ Frequency Sweep:** Professional slider (20Hz - 20,000Hz) for advanced audio testing.
* **📱 PWA Ready:** Installs to the home screen as a native app on iOS and Android.
* **⚡ Zero Latency:** No mp3 files. All sound is synthesized mathematically in real-time.
* **🛡️ Privacy First:** No tracking. No downloads. 100% Client-side execution.

## 🔬 How It Works (The Science)
1.  **Oscillation:** The Javascript engine creates a continuous oscillator node.
2.  **Waveform:** We use a `sawtooth` wave rather than a `sine` wave, as the sharp edges of the sawtooth wave create stronger air percussions.
3.  **Expulsion:** The mechanical vibration overcomes the surface tension of the water, forcing it out of the mesh.

## 🛠️ Technologies Used
* **Core:** HTML5, CSS3 (Glassmorphism / Dark Mode), Vanilla JavaScript.
* **Audio Engine:** Web Audio API (`AudioContext`, `OscillatorNode`, `StereoPannerNode`).
* **Performance:** Zero-dependency architecture. Loads in <50ms.
* **SEO:** Fully optimized with JSON-LD Schema and Open Graph tags.

## 📦 Deployment
This project is a static web application hosted on GitHub Pages.

1.  **Domain:** [waterinmyspeaker.com](https://waterinmyspeaker.com)
2.  **Hosting:** GitHub Pages
3.  **Monetization:** Google AdSense Ready (`ads.txt` included)

## ⚠️ Disclaimer
*This tool generates loud, high-frequency and low-frequency sounds.*
* **Volume Warning:** It is recommended to set volume to 100% for effective cleaning, but keep the device away from sensitive ears during operation.
* **Liability:** While this frequency is standard for speaker cleaning, the developers are not responsible for any hardware damage that may occur during use.

---
&copy; 2026 WaterInMySpeaker.com • Built by Luna Shehab
