# 3D_website_program
# TECHFEST // THE NEXUS GRID

[![Engine: Three.js r128](https://img.shields.io/badge/3D__Engine-Three.js_r128-00f3ff.svg?style=flat-square)](https://threejs.org/)
[![Graphics API: WebGL](https://img.shields.io/badge/Graphics_API-WebGL__Pipeline-b000ff.svg?style=flat-square)](https://developer.mozilla.org/en-US/docs/Web/API/WebGL_API)
[![System Status: Optimal](https://img.shields.io/badge/SYS__STATUS-2026__V1-39ff14.svg?style=flat-square)](#)

The Nexus Grid is an immersive, hardware-accelerated landing terminal designed for Techfest. It integrates a fixed Three.js 3D viewport canvas seamlessly underneath an asynchronous, high-fidelity HUD interface. The architectural layout balances raw WebGL computational pipelines with fluid DOM scroll vectors to achieve multi-layered depth parsing.

---

## ⚡ Core Graphic Engine Capabilities

* **Asynchronous Lerp Pipeline:** Converts standard viewport scrolling deltas into responsive 3D transforms using linear interpolation (Lerp). This mechanism uncouples raw scroll events from rendering cadences, mitigating micro-stuttering.
* **Ambient Particle Network:** Dynamically generates a spherical coordinates matrix containing **2,500 independent vector vertices**. Blends individual blue/purple hex color spectra directly across geometric buffer attributes.
* **Dynamic Vertex Displacements:** Evaluates a continuous sinusoidal drift frequency directly over the particle coordinate positions array inside the rendering pipeline loop, driving complex micro-drift simulations.
* **Spatial Interactive Mesh:** Hosts a centrally isolated 3D Icosahedron wireframe node that parses mouse spatial matrix coordinates, recalculating its position properties in real-time response parameters.

---

## 📂 System File Layout Mapping

```assets/
├── index.html               # Main WebGL Application File Matrix
└── Engine CDN Infrastructure
    └── three.min.js (r128)  # Core Hardware-Isolated Rendering Logic
