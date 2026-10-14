# Echoes of the Hollow Sun

**Echoes of the Hollow Sun** is a browser-based, standalone 2D action-adventure / Metroidvania game built entirely in pure JavaScript and HTML5 Canvas. No external runtime dependencies, servers, or installations are required—just open and play.

---

## 🚀 Features

* **Single-File Architecture:** Runs completely offline directly in any modern web browser.
* **Procedural Audio Engine:** Built-in Web Audio API synthesizer generates retro sound effects and ambient melodies dynamically at runtime.
* **Flexible Input System:** Supports keyboard layouts, standard gamepads (Xbox/PlayStation), and on-screen touch controls for mobile.
* **Persistent Progress:** LocalStorage-backed save system with automated data management and fallback keys.

---

## 🕹️ Controls

| Action | Primary Keyboard | Secondary Keyboard | Gamepad (Standard) |
| :--- | :--- | :--- | :--- |
| **Move Left / Right** | `Arrow Left` / `Arrow Right` | `Key A` / `Key D` | Left Analog Stick / D-Pad |
| **Jump** | `Space` | — | Button 0 (A / Cross) |
| **Attack** | `Key J` | — | Button 2 (X / Square) |
| **Dash** | `Shift Left` | `Shift Right` | Button 1 (B / Circle) |
| **Interact** | `Key E` | `Enter` | Button 3 (Y / Triangle) |
| **Heal** | `Key H` | — | Button 4 (LB / L1) |
| **Magic / Pulse** | `Key Q` | — | Button 5 (RB / R1) |
| **Pause Menu** | `Escape` | `Key P` | Button 9 (Start / Menu) |
| **Map** | `Key M` | — | Button 8 (Select / View) |

---

## 🛠️ Technical Specifications

* **Canvas Resolution:** 480 × 272 pixels (16:9 widescreen retro look)
* **Target Frame Rate:** Fixed delta time loop ($60 \text{ FPS}$)
* **Core Combat Mechanics:** 3-hit melee combo system with active frame detection, custom reach, and escalating damage metrics.

---

## 📂 Getting Started

1. Download or clone your project repository.
2. Open your HTML game file (e.g., `echoes-hollow-sun-enhanced(7).html`) in any modern web browser like Chrome, Firefox, Edge, or Safari.
