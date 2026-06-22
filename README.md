# 🎤 FNF: Graphical Reboot (Console GUI Edition) — by G Studio-Team

[![Project Status: Active](https://shields.io)](#)
[![Platform Compatibility](https://shields.io)](#)
[![License: MIT](https://shields.io)](https://opensource.org)

> **"The console loop is broken. The Evil AI has seized control of the terminal grid. It's time to drop the beat on a brand-new engine."** 
> *— Official Lore Notes by G Studio-Team Lead Writer*

---

## 💾 Welcome to the Architecture Reboot

Welcome to the official repository of **FNF: Graphical Reboot**. After the technical closure and archival of the legacy terminal builds, **G Studio-Team** has officially deployed a bulletproof, crash-free graphical core engine powered entirely by **Tkinter**. 

No more screen flickering. No more terminal array crashes. Just pure rhythm, desktop execution, and mobile touch support.

---

## 🛠️ Global Feature Roadmap

| Feature | Legacy Build (v0.3 Terminal) | Reboot Build (v0.0 GUI Master) | Status |
| :--- | :---: | :---: | :---: |
| **Graphic Framebuffer** | `os.system('clear')` (Flickering) | Native Tkinter Window Layout | **Stable** 🟢 |
| **Input Handler** | Buggy row-matrix index checks | Multi-bound event triggers & Lambda | **Fixed** 🟢 |
| **Mobile Control** | Virtual Keyboards required | 4 Responsive On-Screen Touch Buttons | **Active** 🟢 |
| **Cross-Platform** | Restricted to mobile terminal loops | Standalone Linux desktop binary setup | **Deployed** 🟢 |
| **ASCII State Machine** | Text-only prints | Dynamic font-buffered ASCII label frames | **Active** 🟢 |

---

## 🎮 Game Mechanics & Story Lore

You control **Boyfriend (BF)** inside a secure Unix terminal layer. The **Evil AI** is sending rhythm note arrays down the field grid. To survive, you must hit the matching directions exactly when they enter the **PERFECT ZONE** (Row Index 0).

* **Tug-of-War Health Bar:** Keeping your flow increases your HP ticks. Missing notes allows the Evil AI to counter-attack, shifting the balance of power.
* **Dynamically Scaled Combo Rankings:** Keep your streak alive to unlock dynamic, performance-scaled status updates directly above your scoreboard:
  * `[🔥 COOL]` — Rhythmic activation.
  * `[👑 UNSTOPPABLE]` — Grid domination.
  * `[⚡ GODLIKE]` — Maximum terminal overdrive!

---

## 🕹️ Control Mapping

### For Android Users (PyDroid 3):
Simply launch the code and use the **4 large, colored touch buttons** positioned at the bottom of your smartphone screen. No physical keyboard required!

### For Linux / Desktop Users:
The **Linux Master-Build** explicitly captures both lowercase and uppercase inputs to bypass keyboard layout and `Caps Lock` conflicts:
* **`A` or `a`** ── Left Arrow (`◀`)
* **`S` or `s`** ── Down Arrow (`▼`)
* **`W` or `w`** ── Up Arrow (`▲`)
* **`D` or `d`** ── Right Arrow (`▶`)

---

## 💻 Quick Execution Guide (Linux Desktop)

To grant native execution permissions and launch the **Linux Master-Build** straight from your Unix terminal shell, run the following hooks:

```bash
# Clone the repository
git clone https://github.com

# Enter directory, grant permissions and execute
cd FNF_Python
chmod +x main.py
./main.py
```

---

## 🔮 Future Expansion & Modding Notice
Thanks to the permissive **MIT License**, this project is fully open for community modding, standalone forks, and custom track charting. 

**Want to join G Studio-Team?** Developers who submit high-quality Pull Requests, custom ASCII skins, or rhythm optimization patches will be officially invited into the organization repository workspace as authorized core programmers!

---
🛸 **Developed and published under the creative direction of G Studio-Team.** *Keep the terminal rhythm alive!* 💥🎤🐧
