# Anime.js v4 Landing Page with 3D Anatomy Reveal

A high-fidelity recreation of the **[Anime.js v4](https://animejs.com/)** landing page featuring the iconic interactive 3D camera lens and isometric anatomy reveal dissection, constructed using the assets, 3D models, shaders, and the **Anatomy Reveal** skill.

---

## 🌟 Key Features

1. **All-in-One Hero Animation**:
   - Dynamic typewriter text cycling between `HTML`, `WebGL`, `CSS`, `Canvas 2D`, `SVG`, and `anything`.
   - Glowing circular aperture with 192 radial tick marks, colored perimeter arc segments, and live oscillating cubic-bezier easing waveforms.
   - Interactive `npm i animejs` snippet with instant clipboard copying.

2. **The Complete Animator's Toolbox (Exploded Anatomy Reveal)**:
   - Smooth 3D tilt and pitch as you scroll into the paper-themed section (`#ECE7DF`).
   - Isometric exploded disassembly: curved casing shields slide outward, and 22 internal precision modules separate along the optical axis.
   - Interactive SVG leader lines linking the 5 primary subsystems (`timer`, `easings`, `draggable`, `scroll`, `scope`) directly to their 3D components.
   - Direct link to the pure SVG vector Anatomy Dissection View (`/anatomy/figure-light.html`).

3. **Interactive Timeline & Scrubber Bar**:
   - Sleek pill-shaped scrubber bar at the bottom right with tick marks and a red playback needle.
   - Click or drag anywhere along the track to scrub the entire landing page and lens reveal smoothly from 0% to 100%.

4. **Live Interactive Feature Demos**:
   - **Intuitive API**: Rotating/morphing red rounded cube with live code card.
   - **Enhanced Transforms**: Floating multi-shape composition blend demo.
   - **Scroll Observer**: Geometric wireframe spheres with stroke-dasharray animation synced to scroll.
   - **Advanced Staggering**: 13×13 pulsating dot matrix undulating outward from center.
   - **SVG Toolset**: Race circuit track with animated car following motion paths and stroke drawing.
   - **Springs & Draggable**: Interactive physics draggable node with realistic spring damping.
   - **Runs Like Clockwork**: Precision clock dial with stepping ticks and rotating ticker hand.
   - **Responsive Animations**: Viewport orientation transitions with adaptive dot layouts.

5. **Modular Architecture & Bundle Size Calculator**:
   - Disassembled modules laid out in 3D exploded view with KB badges (`4.30 KB`, `0.50 KB`, `6.37 KB`, `3.13 KB`, etc.).
   - Live interactive bundle size card with a segmented color chart and breakdown (`24.50 KB` total).

6. **Sponsors & Documentation**:
   - Pulsing red heart made of 13×13 dot grid with realistic easing heartbeat.
   - Funding goal progress bar with backer avatars.
   - 12 category documentation cards with color-coded dots and hover states.

---

## 🚀 Running Locally

The local HTTP server serves all static files, WebGL 3D models (`.glb`), Draco WASM decoders (`.wasm`), and JSON endpoints with correct MIME types and CORS headers.

```bash
# Start the server (runs on port 3000 by default)
node server.mjs
```

Open your browser at:
👉 **[http://localhost:3000](http://localhost:3000)**

To directly view the pure SVG Anatomy Reveal figure:
👉 **[http://localhost:3000/anatomy/figure-light.html](http://localhost:3000/anatomy/figure-light.html)**

---

## 📁 Project Structure

```
├── index.html                 # Main Anime.js v4 landing page
├── server.mjs                 # Node.js static server with MIME & WASM support
├── anatomy/                   # Anatomy Reveal skill interactive figures
│   ├── figure.html            # Dark theme vector dissection figure
│   └── figure-light.html      # Light paper-look vector dissection figure
├── assets/
│   ├── css/
│   │   ├── core.css           # Anime.js design system & color tokens
│   │   └── home.css           # Landing page specific styles & layout
│   ├── js/
│   │   ├── home.js            # Main 3D lens & landing page engine
│   │   └── chunks/            # Three.js, Draco, and Anime.js modular chunks
│   ├── models/                # 22 Draco-compressed GLB 3D lens models
│   ├── draco/                 # Draco WASM decoders
│   ├── images/                # Logos and icons
│   └── json/                  # Mathematical easings definitions
└── sponsors/                  # Local sponsor feeds and avatars
```
