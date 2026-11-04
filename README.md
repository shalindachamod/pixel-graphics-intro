# PIXEL GRAPHICS — Iconic Lamp Jump Intro 🎬✨

A high-fidelity, 60fps procedural recreation of the legendary Luxo Jr. lamp jump logo intro, custom-tailored for **PIXEL GRAPHICS**. Built entirely as a single self-contained HTML file with zero external media dependencies—featuring fully procedural canvas kinematics, dynamic volumetric lighting, and a real-time Web Audio API sound synthesis engine.

![HTML5 Canvas](https://img.shields.io/badge/HTML5-Canvas-E34F26?style=flat-square&logo=html5&logoColor=white)
![Vanilla JS](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Web Audio API](https://img.shields.io/badge/Web%20Audio-API-4A90E2?style=flat-square)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-CSS-38Bdf8?style=flat-square&logo=tailwindcss&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green.svg)

---

## 🌟 Key Features

- **Procedural 60fps Kinematics**: Complete multi-joint articulated lamp rig (base, parallel arms, tension springs, rotating 3D flared shade) featuring realistic squash-and-stretch and trailing head overlap.
- **Synthesized Web Audio API Sound Engine**: Zero external audio files (`.mp3`/`.wav`). Every sound effect is procedurally synthesized in real time:
  - Metallic spring tension squeaks & arm creaks
  - Weighted floor landing thuds & rubbery cartoon bounce squishes
  - The iconic final letter flattening splat
  - 60Hz incandescent bulb electrical hum
  - Warm major-ninth cinematic shimmer chord
- **Full 5-Phase Master Choreography (8.60s)**:
  1. *Hop In*: Lamp hops in from the right edge across 3 springy leaps.
  2. *Inspect 'I'*: Stops next to the letter `I`, cranes its neck to scan up the structure, and wiggles in anticipation.
  3. *Stomp & Squash*: Leaps onto the top of the `I` and bounces 4 times, horizontally bulging and flattening the letter into the floor.
  4. *Camera Turn*: Glances around sheepishly and smoothly rotates its 3D lampshade directly toward the camera lens as **GRAPHICS** fades in.
  5. *Finale*: Studio lights dim out, leaving the glowing incandescent bulb and final lockup click.
- **Interactive Studio HUD & Controls**:
  - Real-time interactive timeline scrubber and playback speed toggle (`0.5x`, `1x`, `1.5x`).
  - **Manual Jump (`Spacebar`)** mode.
  - Mouse-tracking lamp aim mode after the intro completes.
  - Studio lights toggle (`Classic Dim Finale` vs `Studio Lights Locked On`).

---

## 🚀 Quick Start / Preview

Because this project is packaged as a **Single-File Application**, running it is effortless:

1. Clone or download this repository:
   ```bash
   git clone https://github.com/your-username/pixel-graphics-intro.git
   ```
2. Open the `index.html` file in any modern web browser (Google Chrome, Safari, Firefox, Edge).
3. Click **"Replay with Sound"** or press **Spacebar** to enjoy the full experience!

---

## 📂 Project Structure

```text
pixel-graphics-intro/
├── index.html       # Complete self-contained application (HTML + CSS + JS + Audio Engine)
└── README.md        # Project documentation
```

---

## 🛠️ Tech Stack

- **Rendering Engine**: HTML5 2D Canvas Context with 2.5D projection matrices.
- **Styling**: Tailwind CSS (via CDN) + Custom glassmorphism UI overlay.
- **Audio**: Native Browser `AudioContext` (Oscillators, Biquad Filters, Gain Nodes, White Noise buffers).

---

## 📜 License

This project is open-source under the [MIT License](LICENSE). Feel free to use, modify, and learn from it!
