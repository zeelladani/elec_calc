<img width="1902" height="911" alt="Screenshot 2026-10-14 032723" src="https://github.com/user-attachments/assets/c4edcb32-4e80-48c2-83bb-a5a5df5a2a2f" />
<img width="1897" height="899" alt="Screenshot 2026-10-14 032751" src="https://github.com/user-attachments/assets/ebf31004-a9f5-4bf9-bd30-c1812ac31c54" />
[view live site](electric.zeelladani.in)


# ⚡ Electrical Calculators

> A free, open-source collection of electrical engineering calculators built for commercial construction — load, cable, fault, protection, lighting, motors, backup power. Every calculator exports a clean PDF of what you see on screen.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![No Build Step](https://img.shields.io/badge/Build-None%20Needed-brightgreen.svg)](#)
[![Made for Engineers](https://img.shields.io/badge/Made%20for-Engineers-blueviolet.svg)](#)

---

## ✨ Features

- **9 live calculators** covering the core commercial electrical design workflow
- **NEC 2023 / ASHRAE 90.1 / NFPA 70E** references baked into every tool
- **Export to PDF** — prints exactly what you see on screen
- **AWG ↔ mm²** side-by-side in cable sizing
- **Responsive** — bento-mosaic layout on mobile, grid on desktop
- **Glassmorphism UI** with your own background photos
- **Ambient background music** with volume + mute (persists across pages)
- **Zero dependencies** — no build step, no framework, no CDN
- **PWA-ready** — works offline once loaded

---

## 🧮 Calculators included

| # | Tool | What it does |
|---|---|---|
| 01 | **Cable Sizing** | Ampacity, derating, AWG ↔ mm², OCPD check per NEC 310.16 |
| 02 | **Voltage Drop** | Single & three-phase feeder + branch, NEC 3%/5% limits |
| 03 | **Load & Demand** | Connected load, demand factor, diversity, LPD check |
| 04 | **Short Circuit** | Point-to-point method, AFC label per NEC 110.24 |
| 05 | **Protection / OCPD** | Breaker sizing, Ib ≤ In ≤ Iz, I²t adiabatic check |
| 06 | **Panel Schedule** | Main breaker, busbar, neutral sizing |
| 07 | **Motor Calc** | NEC 430 FLA table, 125% branch, overload, starting current |
| 08 | **Lighting** | Lumen method, LPD vs ASHRAE 90.1, emergency coverage |
| 09 | **Backup / UPS** | Generator kVA, battery Ah, ATS rating, UPS runtime |

Coming soon: Earthing Design, Solar / PV String, Arc Flash (IEEE 1584), Transformer Sizing.

---

## 🚀 Quick Start

**Option 1 — Just open it**
1. Clone or download this repository
2. Open `index.html` in a browser
3. Done. No build, no install.

**Option 2 — Local server (recommended for music)**
```bash
python3 -m http.server 8000
# then visit http://localhost:8000
