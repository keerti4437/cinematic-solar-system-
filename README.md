# cinematic-solar-system-
a real time 3d particle system made with three.js and assistance of ai tools 
# 🪐 Gravitational Vector Horizon

An immersive, interactive 3D solar system simulator that bridges real-time computer vision telemetry with advanced WebGL graphics. By utilizing **MediaPipe Hand Tracking** and **Three.js**, this project allows users to manipulate gravity, warp cosmic fabrics, and rewrite planetary physics using natural hand gestures through a standard webcam.

## 🚀 Core Features

* **Dual-Stage Kinetic Sequence (Open Palm Toggle):** Flashing an open palm triggers a massive inward gravitational collapse, pulling planets toward the Sun, before seamlessly unfolding them into a perfectly locked, static linear alignment. Flash again to release them back into dynamic orbit.
* **Holographic Gravitational Vector Lines:** Replaces traditional particle grids with 15 highly visible, glowing neon-cyan concentric orbital loops that realistically ripple and deform based on hand height ($Y$-axis warp parameters).
* **High-Fidelity Planetary Profiles:** Includes custom-colored particle configurations, such as a multi-tonal Blue/Green terrain layout for Earth, an isolated secondary equatorial particle system for Saturn's rings, and an enhanced asteroid belt layer.
* **Hyper-Realistic Volumetric Sun:** Powered by a custom GPU fragment shader utilizing multi-layered turbulent thermal noise functions to render blinding white thermal cores fading into incandescent crimson solar flares.
* **Giant HUD Typography:** High-definition billboard typography textures rendered on a $512 \times 128$ canvas structure to guarantee clean text scaling at wide camera views.
* **Micro-Proximity Camera System:** Optimized camera clipping paths allow seamless zoom tracking directly into the geometric core of planetary surfaces without clipping artifacts.

## 🎮 Gesture Telemetry Controls

| Gesture | Physical Action | Cosmic Response |
| :--- | :--- | :--- |
| 🔴 **The Pinch** | Close/Open distance between Thumb & Index tip | Dynamically scales system proportions and planet sizes (Expansion Matrix). |
| 🟢 **The Sweep** | Shift wrist coordinates Left / Right | Controls camera orbital sweeping and side-to-side rotation. |
| 🔵 **The Warp** | Shift wrist coordinates Up / Down | Translates vertical telemetry into custom sine-wave ripples across space-time vectors. |
| ✋ **The Horizon** | Flash an Open Palm | **Stage 1:** Inward gravitational pull cascade.<br>**Stage 2:** Frozen linear planetary alignment lock. (Toggle On/Off) |

## 🛠️ Built With

* [Three.js (r128)](https://threejs.org/) - 3D WebGL Graphic Pipeline rendering
* [MediaPipe Hands](https://google.github.io/mediapipe/solutions/hands.html) - Machine Learning telemetry tracking framework
* **GLSL Shaders** - Custom high-exposure solar plasma simulations

---

## 📦 Local Installation & Setup

Because browser security features restrict webcam permissions on native hard drive files (`file:///`), this project must be hosted through a secure server context (`https://` or `localhost`).

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/YOUR-USERNAME/hand-gesture-solar-system.git](https://github.com/YOUR-USERNAME/hand-gesture-solar-system.git)

  2 
  Open in Browser: Navigate to http://localhost:8000 or deploy directly to GitHub Pages for an out-of-the-box live secure connection!
