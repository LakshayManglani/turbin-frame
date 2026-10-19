# TurbinFrame ⚡

A lightweight, zero-dependency browser tool that wraps any image or screenshot inside a futuristic **Turbin3-inspired cyberpunk HUD frame** without altering, cropping, or filtering the original image.

## ✨ Features

- **Unaltered Source Image**: The uploaded image remains 100% pixel-intact underneath the decorative HUD frame.
- **Cyberpunk HUD Frame**: Chamfered angular borders, multi-tone neon green accents (`#00ff88`), pulsing corner nodes, and circuit traces.
- **Live Customization**:
  - Customizable Brand Title & Subtext
  - Builder Handle (`BUILDER // @username`)
  - Selectable Cohort Date (`YYYY.MM.DD`)
  - Glow Intensity & Frame Padding controls
- **Solid Theme Matting**: Exported images feature a deep dark cyber matting (`#020807`) with ambient radial emerald glow — zero transparency issues or white borders.
- **Dual Export**: 1-click high-resolution (2x Retina) export to **PNG** or **JPG**.
- **100% Client-Side**: No backend, no build tools, no API keys, and works completely in the browser.

## 🚀 Quick Start

Clone the repo and open `index.html` in your browser:

```bash
git clone https://github.com/LakshayManglani/turbin-frame.git
cd turbin-frame
xdg-open index.html  # or double-click index.html
```

## 🛠️ Tech Stack

- **HTML5 & Vanilla JavaScript**
- **Tailwind CSS** (via CDN)
- **html-to-image** (client-side export)
- **Google Fonts** (`Orbitron`, `Rajdhani`, `JetBrains Mono`)
