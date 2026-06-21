# 🎤 Friday Night Funkin': Console Edition (Python)

[![GitHub license](https://shields.io)](https://github.com)
[![GitHub release](https://shields.io)](https://github.com/releases)
[![Python Version](https://shields.io)](https://github.com)

A fully functional rhythm game clone of **Friday Night Funkin'**, written in pure Python 3 to run directly inside the text console (terminal) [📑]. Developed and published by the indie game group **G Studio-Team** 👽.

---

## 📱 Features

- 🚀 **100% Stability:** Built on a turn-based terminal text engine [📑]. This completely bypasses mobile GPU driver issues and prevents crashes on modern smartphones like **Poco X6 Pro** running **HyperOS (Android 14/15)**.
- 🎭 **Dual ASCII Animation (v0.1-alpha):** Both **Boyfriend (BF)** and the **Evil AI (Opponent)** are animated via text sprites and change their singing poses dynamically in real-time [📑].
- 📊 **Dynamic Health Bar (v0.1-alpha):** Features a classic tug-of-war ANSI-colored text health bar [📑]. Hitting notes heals BF and pushes the bar green/cyan; missing notes lets the AI counter-attack and push it magenta/red.
- ⚡ **Precision Rating System:** Evaluates your tap timing instantly (`SICK!!!`, `GOOD!`, `BAD TAP`, `MISS!`).
- ⚖️ **MIT Licensed:** Open-source, modification-friendly, and free to share [📑].

---

## 🎮 Controls

To hit notes perfectly, press the corresponding action key **exactly when a falling arrow enters the top row** (**PERFECT HIT ZONE**):

| Key | Arrow Direction | Symbol |
| :---: | :--- | :---: |
| **`a`** | Left | ◀ |
| **`s`** | Down | ▼ |
| **`w`** | Up | ▲ |
| **`d`** | Right | ▶ |
| **`q`** | Exit Game | ❌ |
| **`Enter`** | Skip Empty Beat | ⏳ |

*Note: Pressing **Enter** without typing a key advances the rhythm track. Do not spam keys without arrows, or you will receive a score and health penalty!*

---

## 🛠️ Installation & Launch Guide

### On Mobile Devices (Android / PyDroid 3):
1. Download **PyDroid 3** from the Google Play Store.
2. Go to the **Releases** tab of this repository and download the `main.py` file from the **Assets** section [📑].
3. Open `main.py` inside PyDroid 3 and hit the big yellow **Play** button.
4. Play right inside your terminal console!

### On Desktop (PC / Mac / Linux):
1. Ensure you have **Python 3.10+** installed.
2. Clone this repository or download the source code.
3. Open your terminal/command prompt in the project folder and run:
   ```bash
   python main.py
   ```

---

## 📑 Changelog (Release Notes)

### 🟢 v0.1-alpha — The Battle Update (Latest)
- **Added:** New **Tug-of-War Health Bar** mechanism using custom ANSI block graphics [📑].
- **Added:** Brand new **AI Opponent animations**! The Evil AI now reacts, shifts color, and mocks you when you miss notes [📑].
- **Added:** Win/Loss condition screens (Survive up to 1500 points or 100% HP to win).
- **Fixed:** Critical syntax crash (`NameError`) regarding color variables on Python 3.13 [📑].

### ⚪ v0.0-prototype — Initial Technical Demo
- Initial terminal grid render engine release.
- Basic input handler and Boyfriend ASCII dancing poses.

---
Developed with 🤖 by **G Studio-Team** 
