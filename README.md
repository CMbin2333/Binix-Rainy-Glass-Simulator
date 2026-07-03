---
AIGC:
    Label: "1"
    ContentProducer: 001191440300708461136T1XGW3
    ProduceID: 8c1392e23868e04d404619f18f58a936_64400112770011f19641525400d9a7a1
    ReservedCode1: bDxbCjIuTxAcRkvOj9JYpfjku8pe42mFtFWkWxuN/8aG7ac5FgrP/P79K8JF+B5DtjHFMqgKEC6OhrxCKs/7VtbPU336u9rMQ4m0PAfBHDlGEvj4zvJgApIp5a0VyJyARjuTyMcyTW0dg6NPI3UAvRifM70nVFjgBaRxlv+VdeBb5y7XQ0AQedL4gZk=
    ContentPropagator: 001191440300708461136T1XGW3
    PropagateID: 8c1392e23868e04d404619f18f58a936_64400112770011f19641525400d9a7a1
    ReservedCode2: bDxbCjIuTxAcRkvOj9JYpfjku8pe42mFtFWkWxuN/8aG7ac5FgrP/P79K8JF+B5DtjHFMqgKEC6OhrxCKs/7VtbPU336u9rMQ4m0PAfBHDlGEvj4zvJgApIp5a0VyJyARjuTyMcyTW0dg6NPI3UAvRifM70nVFjgBaRxlv+VdeBb5y7XQ0AQedL4gZk=
---

<!--
  AIGC:
    Label: "1"
    ContentProducer: 001191440300708461136T1XGW3
    ProduceID: 8c1392e23868e04d404619f18f58a936_d883228c76fd11f1a7da5254006c9bbf
    ReservedCode1: cVL/iKZvsnDsIpVQcR7wGhkSDUc0jnZkV1qdxprk7OBcFsR9cFdhxNlY8aUDSJagh4llj25J5CeaO8xkIvndYfYam9fbOh1OWrp/AslUEoYV7maFVVjW6KyWp16iGSdRByv9BweND4qG+e4CZptztXnJ+5B8uF1lr4FvpXX/kP7IBPiWrcJBxiHltGE=
    ContentPropagator: 001191440300708461136T1XGW3
    PropagateID: 8c1392e23868e04d404619f18f58a936_d883228c76fd11f1a7da5254006c9bbf
    ReservedCode2: cVL/iKZvsnDsIpVQcR7wGhkSDUc0jnZkV1qdxprk7OBcFsR9cFdhxNlY8aUDSJagh4llj25J5CeaO8xkIvndYfYam9fbOh1OWrp/AslUEoYV7maFVVjW6KyWp16iGSdRByv9BweND4qG+e4CZptztXnJ+5B8uF1lr4FvpXX/kP7IBPiWrcJBxiHltGE=
-->

# Binix Rainy Glass Simulator / 心雨 · 玻璃雨滴模拟器

[![WebGL2](https://img.shields.io/badge/WebGL-2.0-red.svg)](https://www.khronos.org/webgl/)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![React](https://img.shields.io/badge/React-19.2-61dafb.svg)](https://react.dev/)
[![TailwindCSS](https://img.shields.io/badge/TailwindCSS-4.3-38bdf8.svg)](https://tailwindcss.com/)
[![GLSL](https://img.shields.io/badge/GLSL-460-orange.svg)](https://www.khronos.org/opengl/wiki/Core_Language_(GLSL))
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

> A beautifully crafted, GPU-accelerated WebGL2 glass raindrop simulator. Real-time physics, cinematic motion blur, 3D lighting, and an interactive control panel — all running in a single fragment shader.
>
> 一个精美的 GPU 加速 WebGL2 玻璃雨滴模拟器。实时物理、电影级运动模糊、3D 光照、交互式控制面板 — 全部运行在单个片元着色器中。

---

<p align="center">
<img width="2560" height="1347" alt="PixPin_2026-07-04_01-09-28" src="https://github.com/user-attachments/assets/29fe1805-afbd-47b8-976b-65f84d635396" />
</p>

<p align="center">
  <em>Default scene — glass beads with falling raindrops over a blurred backdrop</em>
</p>

---

## Table of Contents

- [Live Demo / 在线演示](#live-demo--在线演示)
- [Screenshots / 截图展示](#screenshots--截图展示)
- [Features / 功能特性](#features--功能特性)
- [Rendering Pipeline / 渲染管线](#rendering-pipeline--渲染管线)
- [Control Panel / 控制面板](#control-panel--控制面板)
- [Tech Stack / 技术栈](#tech-stack--技术栈)
- [Quick Start / 快速开始](#quick-start--快速开始)
- [File Structure / 文件结构](#file-structure--文件结构)
- [Performance Optimization / 性能优化](#performance-optimization--性能优化)
- [Browser Compatibility / 浏览器兼容性](#browser-compatibility--浏览器兼容性)
- [FAQ / 常见问题](#faq--常见问题)
- [Inspiration & Credits / 灵感与致谢](#inspiration--credits--灵感与致谢)
- [Star History / Star 历史](#star-history--star-历史)
- [License / 许可证](#license--许可证)

---

## Live Demo / 在线演示

> 🚀 Try it instantly: open `index.html` in any WebGL2-capable browser.
> No build, no install, no server needed.

| Demo | Link |
|------|------|
| GitHub Pages | *[coming soon]* |
| Vercel | *[coming soon]* |

---

## Screenshots / 截图展示

<p align="center">
    <img width="2560" height="1347" alt="image" src="https://github.com/user-attachments/assets/ad3ac03c-9ee1-46ec-8c38-f85352e01a1f" />
    <img width="2560" height="1347" alt="image" src="https://github.com/user-attachments/assets/e62dedd3-9a91-463a-b973-651b4eb64899" />
    <img width="2560" height="1347" alt="image" src="https://github.com/user-attachments/assets/c3b2eea6-1643-45c3-a1e7-961139e5e434" />
    <img width="2560" height="1347" alt="image" src="https://github.com/user-attachments/assets/87c36708-1e51-41b2-91d7-8c18fa776a4e" />
</p>

> 💡 *To capture your own screenshots: right-click the canvas and "Save as Image", or use the browser's built-in screenshot tool.*

---

## Features / 功能特性

### Core Simulation / 核心模拟

| Feature | Description |
|---------|-------------|
| **Multi-layer Rain System** | 3 independent layers: static glass beads, dynamic falling drops (Layer 1), secondary detail drops (Layer 2), plus fast-sliding drops |
| **Realistic Drop Physics** | Non-linear stop-and-go warping, organic wiggle-wave motion, per-column randomized speed & size |
| **Drop Trails & Smears** | Translucent streaks behind each falling drop, with configurable intensity and decay |
| **Metaball Fusion** | Fluid density-field merging — when static beads and sliding drops approach, they stretch, bridge, and organically merge |
| **Glass Bead Rendering** | Hexagonal grid distribution, density-based sizing, neighbor-aware blending, per-bead random growth thresholds with fade-in |
| **Fog / Mist Overlay** | Variable atmospheric fog simulating condensation, dynamically adjustable in real-time |
| **Refraction & Distortion** | Light bending through water droplets via normal-map-derived UV offsets |
| **Directional Motion Blur** | Multi-sample vertical blur within drop interiors for cinematic realism |
| **3D Glass Lighting** | Specular highlights (configurable angle), soft shadow borders, dark refractive edges around each droplet |
| **Lightning Flashes** | Stochastic triple-peak lightning with variable frequency, intensity, and organic flickering |
| **Wipe Recovery** | After a drop passes, the fog smoothly recovers with a natural condensation fade-in |

### Interaction / 交互

| Feature | Description |
|---------|-------------|
| **Mouse / Touch Wipe** | Wipe away fog with cursor or finger, revealing the clear view through the glass |
| **Real-time Control Panel** | Sleek glass-morphism UI to tweak every simulation parameter on the fly |
| **Heart-shaped Visual Effects** | Romantic heart-shaped rain patterns as a special emotional mode |
| **Ambient Rain Soundscape** | Immersive rain audio via Web Audio API, responding to rain intensity |
| **Background Toggle** | Switch between loaded backdrop and dark raindrop-only mode |

### Visual & Styling / 视觉与风格

| Feature | Description |
|---------|-------------|
| **4 Display Modes** | Fill (Cover), Contain (Fit), Tile, Stretch — adapt the background to any aspect ratio |
| **Rain Tint Color** | Custom RGB overlay for raindrops to match any mood or theme |
| **Color Filter Effects** | Dynamic temporal color grading with edge vignette |
| **Dark Glass-morphism UI** | Teal/Emerald accent palette with backdrop blur |
| **Wipe Highlight Glow** | Erased spots emit a luminous glow for visual emphasis |

---

## Rendering Pipeline / 渲染管线

The entire simulation is executed inside a single WebGL2 **fragment shader** (fullscreen quad pass), meaning all computation happens on the GPU with zero CPU overhead per frame.

### Pipeline Overview

```
[Uniforms & Textures] ──► Fragment Shader ──► gl_FragColor
     │                        │
     ├─ iChannel0 (bg)        ├─ StaticDrops()     ← Hexagonal glass beads
     ├─ u_erasedMask (wipe)   ├─ DropLayer2() × 2  ← Dynamic falling drops
     ├─ u_rainIntensity...    ├─ DropLayerFast()   ← Fast-sliding drops
     └─ u_highlightAngle...   ├─ Drops()           ← Metaball merge + clear logic
                              ├─ Motion Blur       ← Multi-sample vertical blur
                              ├─ Normal Derivation ← dx/dy finite differences
                              ├─ 3D Lighting       ← Shadow + specular + edge
                              ├─ Tint / Filter     ← Color grading
                              └─ Lightning         ← Stochastic flash overlay
```

### 1. Static Glass Beads (`StaticDrops`)

- Hexagonal grid parameterization via `N13()` hash function
- Each cell gets a random bead position (`(nn.xy - 0.5) * 0.7`), size threshold, and fade-in
- Neighbor sampling (8-way, toggleable) prevents clipping at grid boundaries
- Density-scaled local sizing: `clampedSize = clamp(u_beadScale * activeRecovery * scaleFactor, 0.0, 1.2)`
- Wipe recovery: surrounding beads reappear with a smooth fade when fog is removed

### 2. Falling Raindrops (`DropLayer2`)

- Single drop per 17×17 grid cell, random spawn via hash seeds
- Spiral-based local coordinates for organic distribution within each cell
- Envelope-modulated fall progress: `warpedProgress = progress - env * sin(progress * 6.28 * freq + phase) * intensity`
  - Creates stop-and-go motion with random frequency and phase per cell
- Wave/wiggle: `sin(uv.y * 8.0 * wiggleFreq + t * 5.0) * 0.04 * wiggleScale`
- Trail rendering: `S(0.20 * u_smearPower * (0.4 + r * 0.6), 0.0, cd) * r * presence`
- Adjacent column sampling (2-way neighbor, toggleable) for edge continuity

### 3. Fast-Sliding Drops (`DropLayerFast`)

- 7-column horizontal split for natural dense rain appearance
- Per-cycle random size, speed, and horizontal shift
- Full vertical boundary clamping: `mix(topBoundary, bottomBoundary, warpedProgress)`
- Swallow/sweep mechanics: as a drop passes, it clears static beads beneath it
  - `swallow`: smooth contact-area blending (Metaball merge)
  - `sweep`: exponential decay trail for natural recovery fade-in

### 4. Metaball Density-Field Fusion

All static beads and dynamic drops are summed before thresholding:

```glsl
float c = s + big1 + big2 + big3;
c = S(0.3, 1.0, c);
```

This produces fluid-like bridging and organic merger when droplets approach each other — no hard cutoffs, no overlapping artifacts.

### 5. Normal / Refraction

Finite-difference normals are derived by sampling the drop field at `(uv + epsilon, t)` and `(uv, t + epsilon.yx)`:

```glsl
vec2 n = vec2(cx - c.x, cy - c.x) * u_distortion;
```

This normal is then used for:
- **Refraction** — offsetting the background texture lookup: `targetUV = bgUV + n`
- **3D Lighting** — shadow, border shadow, and specular highlight calculations

### 6. Motion Blur

When `u_blurStrength > 0`, the drop field is sampled 5 times along the vertical axis (multi-sample), and the background is also sampled 5 times inside refraction areas:

```glsl
float blurDist = 0.045 * u_blurStrength * (1.0 + u_fallRate * 1.5) * c.x;
for (float i = 0.0; i < 5.0; i++) { ... }
```

The blur distance scales with drop presence (`c.x`) and fall rate, producing stronger blur on faster-moving drops.

### 7. 3D Lighting

```glsl
float shadow = max(0.0, dot(normN, lightDir));
float shadEffect = pow(shadow, 6.0) * 0.25 * S(0.01, 0.1, nLen);
float borderShadow = S(0.15, 0.25, c.x) * S(0.4, 0.25, c.x) * 0.25;
```

- **Soft shadow** on bottom-right (dot product with light direction)
- **Dark refractive border** via dual smoothstep on drop presence
- **Specular highlight** at configurable angle (`u_highlightAngle`), pow(spec, 10)

### 8. Lightning (`getLightning`)

- Time is skewed: `skewedTime = time + sin(time * 0.5) * 1.5 + cos(time * 0.15) * 2.0`
- 75% probability per irregular cycle period
- Triple-peak strike: main (15 Hz decay), secondary (9 Hz, 0.1-0.22s delay), tertiary (4 Hz, 0.3-0.45s delay)
- Organic flickering: `strength *= 0.5 + 0.5 * sin(time * (100.0 + n.z * 50.0))`
- Randomized brightness: `strength *= 0.4 + 0.6 * n.y`

---

## Control Panel / 控制面板

<p align="center">
  <img width="582" height="1282" alt="image" src="https://github.com/user-attachments/assets/6d5ef87e-9d7e-4ca3-b38e-43391d03fbae" />
</p>

All parameters can be adjusted in real-time via the glass-morphism control panel. Click the gear icon in the top-right corner to open it.

### Parameter Reference / 参数说明

| # | Parameter | Range | Default | Description |
|---|-----------|-------|---------|-------------|
| 1 | **Rain Intensity** | 0.0 – 1.0 | 0.5 | Overall rainfall density. Affects static bead count, layer blending weights, and fog |
| 2 | **Fall Rate** | 0.0 – 2.0 | 1.0 | Speed multiplier for falling rain. Higher = faster drops and stronger motion blur |
| 3 | **Bead Scale** | 0.0 – 2.0 | 0.85 | Size multiplier for static glass beads on the hexagonal grid |
| 4 | **Bead Radius** | 0.0 – 1.5 | 0.6 | Base radius for sliding rain droplets (layer 1 + fast drops) |
| 5 | **Drop Friction** | 0.0 – 1.0 | 0.3 | Controls wiggle/wave intensity during fall. 0 = smooth, 1 = aggressive organic motion |
| 6 | **Drop Stretch** | 0.5 – 3.0 | 1.5 | Vertical elongation of rain drops (simulates wind / gravity stretching) |
| 7 | **Smear Power** | 0.0 – 2.0 | 0.8 | Intensity of the translucent trail left behind each rain drop |
| 8 | **Smear Decay** | 0.1 – 5.0 | 2.0 | How quickly trails fade. Lower = longer trails, higher = stubbier |
| 9 | **Distortion** | 0.0 – 3.0 | 1.5 | Refraction strength — controls how much the background is warped through water |
| 10 | **Blur Strength** | 0.0 – 1.0 | 0.4 | Multi-sample motion blur intensity inside refraction areas |
| 11 | **Fog Density** | 0.0 – 10.0 | 4.0 | Atmospheric mist level. Simulates condensation on glass. Wipe with mouse to clear |
| 12 | **Highlight Angle** | 0° – 360° | 135° | Direction of specular light highlight on droplets (in degrees) |
| 13 | **Flash Intensity** | 0.0 – 2.0 | 0.6 | Brightness of lightning flashes |
| 14 | **Flash Frequency** | 0.1 – 5.0 | 1.5 | How often lightning strikes occur |

### Toggle Switches

| Switch | Effect |
|--------|--------|
| **Show Backdrop** | Toggle between background image and dark-only raindrop mode |
| **Performance Mode** | Disable neighbor sampling to reduce GPU load |
| **Rain Tint** | Enable custom color overlay on raindrops |
| **Color Filter** | Enable dynamic color grading + vignette |
| **Heart Effect** | Switch to heart-shaped rain pattern |

---

## Tech Stack / 技术栈

| Technology | Purpose |
|------------|---------|
| **WebGL2** | GPU-accelerated rendering pipeline with fullscreen quad pass |
| **GLSL (ES 3.0)** | Fragment shader — all raindrop physics, lighting, and post-processing |
| **React 19.2** | UI framework for the interactive control panel |
| **Tailwind CSS 4.3** | Utility-first styling with custom glass-morphism design system |
| **Vite** | Build tool and dev server (for development) |
| **Web Audio API** | Procedural ambient rain soundscape generation |
| **Google Fonts** | Space Grotesk (headings), Inter (body), JetBrains Mono (code) |

---

## Quick Start / 快速开始

### Prerequisites

- A modern browser with **WebGL2** support (Chrome 56+, Firefox 51+, Edge 79+, Safari 15+)
- No Node.js, no build step, no dependencies for basic usage

### Option 1: Direct Open (Zero Setup)

1. **Download or clone** the project:
   ```bash
   git clone https://github.com/your-username/rainy-glass-simulator.git
   ```

2. **Double-click `index.html`** — that's it.

### Option 2: Local Dev Server

> Recommended for the control panel (ES module loading):

```bash
# Using npx (zero install)
npx serve .

# Or Python
python -m http.server 8080

# Or with Vite dev server
npm install && npm run dev
```

Then open `http://localhost:3000` (or the port shown in terminal).

### Controls

| Action | How |
|--------|-----|
| Wipe glass | Click & drag mouse / touch and swipe |
| Open panel | Click the gear icon (top-right corner) |
| Toggle heart | Enable "Heart Effect" in control panel |
| Adjust params | Use sliders in control panel |

---

## File Structure / 文件结构

```
rainy-glass-simulator/
├── index.html              # Minimal HTML shell with fullscreen canvas
├── style.css               # Tailwind CSS 4 + custom glass-morphism styles
├── script.js               # Bundled React 19 app + WebGL2 engine + GLSL shader
├── preview.png             # Main preview screenshot
├── screenshots/            # Gallery screenshots (add your own!)
│   ├── demo-01-default.png
│   ├── demo-02-heart.png
│   ├── demo-03-wipe.png
│   ├── demo-04-control-panel.png
│   ├── demo-05-lightning.png
│   └── demo-06-closeup.png
├── package.json            # Vite + React dev dependencies (optional)
├── vite.config.js          # Vite configuration (optional)
├── LICENSE                 # MIT License
└── README.md               # This file
```

> **Note:** The project is intentionally distributed as a single-file HTML/CSS/JS bundle for maximum portability. The `script.js` contains all React components and GLSL shader code compiled by Vite.

---

## Performance Optimization / 性能优化

The shader employs several optimization strategies to maintain smooth 60fps across devices:

### GPU-Level Optimizations

| Technique | Detail |
|-----------|--------|
| **Single Draw Call** | The entire simulation runs in one fullscreen quad pass — no multi-pass overhead |
| **Performance Mode Toggle** | `u_perfOptimization` disables 8-way neighbor sampling for static beads, 2-way neighbor for dynamic drops, and the secondary drop layer entirely |
| **Early Exit** | Lightning function returns 0 immediately when `n.x > 0.25` (75% of cycles) |
| **Presence Gating** | Dynamic drops with `nPresence < 0.001` skip all neighbor computations |
| **Zero-Branch Loops** | All `for` loops use constant bounds — compiled to unrolled instructions on most GPUs |
| **Resolution-Agnostic UV** | All coordinates normalized to `[-0.5 * u_viewScale, 0.5 * u_viewScale]`, decoupling computation from canvas resolution |

### Performance Mode Impact

| | Normal Mode | Performance Mode |
|---|---|---|
| Callers per StaticDrops | 1 + 8 neighbors = 9 | 1 (no neighbors) |
| DropLayer2 instances | 2 (layer1 + layer2) | 1 (layer1 only) |
| Neighbor columns per DropLayerFast | 2 | 0 |
| Estimated GPU savings | baseline | ~60% fewer neighbor ops |

> **Recommendation:** Enable Performance Mode on integrated GPUs (Intel UHD, Apple M1 base) or mobile browsers. Dedicated GPUs (NVIDIA/AMD) can comfortably run Normal Mode.

---

## Browser Compatibility / 浏览器兼容性

| Browser | Version | WebGL2 | Notes |
|---------|---------|--------|-------|
| Chrome | 56+ | ✅ Full | Best performance |
| Firefox | 51+ | ✅ Full | Good, slightly slower on macOS |
| Edge | 79+ | ✅ Full | Chromium-based, same as Chrome |
| Safari | 15+ | ✅ Full | WebGL2 supported since Safari 15 |
| Opera | 43+ | ✅ Full | Chromium-based |
| Mobile Chrome | 56+ | ✅ Full | Touch wipe works natively |
| Mobile Safari | 15+ | ✅ Full | iOS 15+ required |

> ⚠️ **Internet Explorer** is not supported. WebGL2 is not available on any IE version.

---

## FAQ / 常见问题

<details>
<summary><strong>Q: Why does the page show a blank/black screen?</strong></summary>

**A:** Your browser may not support WebGL2. Check by visiting [get.webgl.org/webgl2](https://get.webgl.org/webgl2/). If WebGL2 is supported but the issue persists, ensure hardware acceleration is enabled in your browser settings.
</details>

<details>
<summary><strong>Q: Can I use my own background image?</strong></summary>

**A:** Yes. Replace the `background.jpg` (or the image referenced in `script.js`'s `iChannel0` texture) with your own image. The display mode (Fill/Contain/Tile/Stretch) can be adjusted in the control panel to best fit your image's aspect ratio.
</details>

<details>
<summary><strong>Q: How do I record a demo video / GIF?</strong></summary>

**A:** Use [ScreenToGif](https://www.screentogif.com/) (Windows), [Kap](https://getkap.co/) (macOS), or [OBS Studio](https://obsproject.com/) (cross-platform). For best results, record at 1920×1080, 60fps, and enable the heart effect + lightning for the most visually appealing output.
</details>

<details>
<summary><strong>Q: The rain sound is too loud / quiet. Can I adjust it?</strong></summary>

**A:** Currently the audio volume is tied to rain intensity (higher intensity = more prominent rain sound). A dedicated volume slider is planned for a future release. In the meantime, you can adjust your system or browser volume.
</details>

<details>
<summary><strong>Q: Why are droplets clipped at cell boundaries?</strong></summary>

**A:** This happens when Performance Mode is enabled, which disables neighbor-cell sampling. Turn off Performance Mode in the control panel to enable cross-cell blending for seamless droplet rendering.
</details>

<details>
<summary><strong>Q: How does the heart effect work technically?</strong></summary>

**A:** The heart shape is rendered through a mathematical heart curve equation applied in the `StaticDrops` function. When enabled, all static glass beads are constrained to form a heart silhouette rather than a full-screen hexagonal grid. This is done entirely in the GLSL shader — no additional geometry or textures are used.
</details>

<details>
<summary><strong>Q: Can I embed this on my website?</strong></summary>

**A:** Absolutely! The project is MIT-licensed. Simply include the three files (`index.html`, `style.css`, `script.js`) and reference them. For embedding in an iframe, ensure the parent page allows WebGL2 contexts. Attribution is appreciated but not required.
</details>

<details>
<summary><strong>Q: How can I contribute?</strong></summary>

**A:** PRs are welcome! Some ideas for contributions:
- Adding new visual effects (snow mode, rainbow droplets)
- Improving mobile performance
- Adding a screenshot/capture button
- Internationalization (i18n) for the control panel
- Custom background upload via drag & drop

Please open an issue first to discuss your idea before submitting a PR.
</details>

---

## Inspiration & Credits / 灵感与致谢

### Inspiration

- The raindrop rendering approach is inspired by the incredible [Shadertoy](https://www.shadertoy.com/) community, particularly the seminal raindrop shaders by **iq**, **BigWIngs**, and **Shane**
- The metaball fluid-merging technique draws from the classic **"Metaball" / "Marching Squares"** rendering papers (Blinn, 1982; Wyvill et al., 1986)
- The non-linear stop-and-go warping is an original implementation of envelope-modulated progress with randomized frequency/phase per column, inspired by natural rain behavior observed in high-speed photography

### Built With

| Resource | Usage |
|----------|-------|
| [Shadertoy](https://www.shadertoy.com/) | Community shader techniques & noise functions |
| [Google Fonts](https://fonts.google.com/) | Space Grotesk, Inter, JetBrains Mono |
| [Tailwind CSS](https://tailwindcss.com/) | Glass-morphism UI framework |
| [React](https://react.dev/) | Interactive control panel |
| [Vite](https://vitejs.dev/) | Build tooling |

### Special Thanks

- **iq** (Íñigo Quílez) — for pioneering real-time raindrop rendering on Shadertoy and inspiring countless shader artists
- **The WebGL Working Group** at Khronos — for making GPU computing accessible on the web
- **Meta (React team)** — for React 19 and the concurrent rendering model
- Everyone who starred, forked, or shared this project

---

## Star History / Star 历史

<p align="center">
  <a href="https://star-history.com/#your-username/rainy-glass-simulator&Date">
    <img src="https://api.star-history.com/svg?repos=your-username/rainy-glass-simulator&type=Date" alt="Star History Chart" width="600" />
  </a>
</p>

> 💡 *Replace `your-username/rainy-glass-simulator` with your actual GitHub repository path to render your real Star History chart.*

---

## Acknowledgments / 致谢

- Shader logic inspired by [Cherry Lab / Heartfelt](https://github.com/cherrychu07/Cherry-Lab) by [@cherrychu07](https://github.com/cherrychu07) — a beautiful WebGL2 glass rain simulation that sparked this project.
- Built with [React](https://react.dev/), [Vite](https://vite.dev/), [Tailwind CSS](https://tailwindcss.com/), and [WebGL2](https://www.khronos.org/webgl/).

---

## License / 许可证

MIT © Binix

```
Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:
...
```

See [LICENSE](LICENSE) for the full text.

---

<p align="center">
  <sub>Made with ❤️ and a lot of GLSL</sub>
</p>
