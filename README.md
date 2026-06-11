# 🌌 Solar System Explorer — Three.js Edition

An interactive 3D Solar System for kids, built with **Three.js r160**, deployable as a single `index.html` on GitHub Pages — no build step, no npm, no server.

---

## ✨ Features

| Feature | Details |
|---|---|
| 🪐 All 8 Planets + Sun | Procedurally textured in native colours |
| 🌀 Live Orbital Animation | Relative speeds, axial tilts, self-rotation |
| 🔍 Click to Zoom | Smooth camera tween to any body |
| 💬 Hover Tooltip | Mass · Diameter · Distance · Rotation speed · Revolution speed · Moons |
| 📖 Detail Panel | Full description, stats grid, moon list, 4 fun facts |
| 🪐 Saturn's Rings | Ring geometry with transparent gradient texture |
| 🌕 Earth's Moon | Real-time orbit around Earth |
| 🌍 Earth Texture | Procedural ocean + continents + ice caps |
| 🟠 Jupiter Bands | Procedural storm bands + Great Red Spot |
| ⭐ 8,000 Stars | Coloured point-cloud starfield |
| ☀️ Sun Corona | Additive blending glow sprite |
| 🏷️ Planet Labels | Canvas overlay labels in Orbitron font |
| ⚡ Speed Control | Slow 🐢 / Normal 🚀 / Fast ⚡ |
| 📱 Touch Support | Mobile drag + tap to zoom |

---

## 🛠 Tech Stack

| Layer | Technology |
|---|---|
| 3D Engine | Three.js r160 (ES module, unpkg CDN) |
| Camera | OrbitControls (damping, min/max radius) |
| Textures | Procedural CanvasTexture (zero external images) |
| Fonts | Google Fonts — Orbitron + Rajdhani |
| Deployment | GitHub Pages (single HTML file) |

---

## 📂 File Structure

```
/
├── index.html   ← entire app in one file, zero dependencies to install
└── README.md
```

---

## 🚀 Deploy to GitHub Pages

```bash
# 1. Create a new repo on github.com, e.g. "solar-system-kids"
# 2. Clone it locally
git clone https://github.com/YOUR_USERNAME/solar-system-kids.git
cd solar-system-kids

# 3. Copy index.html here
cp /path/to/index.html .

# 4. Push
git add .
git commit -m "🚀 Launch Solar System Explorer"
git push

# 5. Enable Pages:
#    Repo → Settings → Pages → Source: Deploy from branch → main / root → Save
```

Live at: `https://YOUR_USERNAME.github.io/solar-system-kids/`

---

## 🎮 Controls

| Action | Effect |
|---|---|
| **Hover** over any body | Shows stats tooltip |
| **Click** "More Details" | Opens full detail panel |
| **Click** any body | Camera zooms to it |
| **Left drag** | Orbit / rotate view |
| **Right drag** | Pan |
| **Scroll / pinch** | Zoom in / out |
| **Speed buttons** | Change orbital animation speed |

---

## 🪐 Celestial Bodies

| Body | Colour | Type | Moons |
|---|---|---|---|
| ☀️ Sun | Orange-gold glow | Star | — |
| ⚫ Mercury | Grey-brown | Terrestrial | 0 |
| 🌕 Venus | Pale gold | Terrestrial | 0 |
| 🌍 Earth | Blue-green | Terrestrial | Moon |
| 🔴 Mars | Red-orange | Terrestrial | Phobos, Deimos |
| 🟠 Jupiter | Tan + bands | Gas Giant | 95+ |
| 🪐 Saturn | Gold + rings | Gas Giant | 146+ |
| 🔵 Uranus | Cyan | Ice Giant | 27 |
| 🌊 Neptune | Deep blue | Ice Giant | 16 |

---

## 📝 License

MIT — free for educational use, sharing, and modification.
