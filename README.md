<div align="center">

# 🌌 BLACKHOLE DELIVERY

### A cosmic-chaos arcade game from **BEURA LABS**

**Swallow the shipment. Grow your gravity. Find the portal. Try not to eat the wrong thing.**

<a href="https://blackhole-delivery.vercel.app">
  <img src="https://img.shields.io/badge/PLAY%20BLACKHOLE%20DELIVERY-LAUNCH%20GAME-ff9a2e?style=for-the-badge&logo=vercel&logoColor=white" alt="Launch Blackhole Delivery" />
</a>

<br />

<img src="https://img.shields.io/badge/PLATFORM-Browser-4de8ff?style=flat-square" alt="Browser game" />
<img src="https://img.shields.io/badge/BUILT%20WITH-HTML5%20%7C%20CSS%20%7C%20JavaScript-ff4fa3?style=flat-square" alt="HTML5, CSS, JavaScript" />
<img src="https://img.shields.io/badge/FORMAT-Single%20HTML%20File-9d8bff?style=flat-square" alt="Single HTML file" />
<img src="https://img.shields.io/badge/RIGHTS-Proprietary-f6efe3?style=flat-square" alt="Proprietary project" />

</div>

---

## ✦ The mission

You are a growing black hole with a delivery order and a deeply questionable relationship with city infrastructure.

Move through handcrafted arenas, pull objects into your event horizon, build mass, and collect the required shipment. Once the order is complete, locate the glowing portal and escape. Larger objects become edible as your black hole grows, but **white gift boxes are forbidden**. Eat one and the delivery clock takes a penalty. Your customers, it seems, have standards.

**Blackhole Delivery** is a self-contained, browser-based arcade game designed by **Beura Labs**. It runs from a single HTML file, with no framework or package installation required.

## 🚀 What’s inside

- **16 delivery missions** spread across **8 themed worlds**, from a Storage Yard to *The Impossible Delivery*.
- **Gravity-driven gameplay** with objects pulled toward your black hole, collisions, growth, and increasingly massive targets.
- **Two abilities:** use **PULSE** to pull nearby objects harder, or **DASH** to burst across the arena.
- **Mission objectives** that range from collecting specific objects to swallowing a target count before the timer expires.
- **Scoring and combos**, including chain multipliers, chain reactions, penalties, and near-miss tracking.
- **Portal extraction:** finish the shipment, follow the direction indicator, and reach the portal to complete the run.
- **Star-rated results** and a delivery map that tracks saved mission progress.
- **Personal settings** for music, sound effects, vibration, and graphics quality.
- **Mobile-first controls** with pointer/touch input alongside keyboard controls for desktop play.

## 🪐 Explore the worlds

| World | The vibe |
|---|---|
| 01 · Storage Yard | A warm-up among crates, barrels, cones, and everyday clutter |
| 02 · Downtown | Street furniture, vehicles, and urban chaos |
| 03 · Industrial Zone | Heavy containers and hazardous cargo |
| 04 · Port | A waterfront freight run |
| 05 · Metropolis | Bigger streets and bigger things to swallow |
| 06 · Future City | Sleek colours, buses, buildings, and valuable relics |
| 07 · Orbital Facility | A high-stakes industrial arena |
| 08 · The Impossible Delivery | The final test of mass, timing, and restraint |

Each world contains two missions, with different target types, counts, time limits, and environmental challenges.

## 🎮 Controls

| Action | Touch / mobile | Keyboard |
|---|---|---|
| Move the black hole | Drag anywhere on the playfield | **WASD** or **Arrow keys** |
| PULSE | Tap the **PULSE** button | **E** |
| DASH | Tap the **DASH** button | **Space** |
| Restart mission | Tap **↻** | Use the restart button |
| Open the delivery map / home | Tap **⌂** | Use the on-screen control |

**A good first run:** start with small objects, build mass gradually, then go after the delivery target. When the objective switches to **DELIVER TO PORTAL**, stop hoovering up the scenery and head for the glowing exit.

## 🧠 Gameplay loop

1. **Read the order.** Check the target and required quantity at the top of the screen.
2. **Build mass.** Pull in objects small enough for your current black hole.
3. **Avoid the forbidden cargo.** White gift boxes trigger a time penalty.
4. **Use abilities thoughtfully.** PULSE helps gather nearby objects; DASH provides a short burst of movement. Watch their cooldown indicators.
5. **Finish the order.** Once the target count is met, make your way to the portal.
6. **Earn your stars.** Better times and avoiding penalties improve the final rating.

## 🛠️ Technology

- **HTML5 Canvas** for real-time rendering and visual effects
- **Vanilla JavaScript** for game logic, physics-style movement, collisions, scoring, and state
- **CSS** for responsive overlays and interface styling
- **Web Audio API** for synthesized sound effects and music tones
- **Local Storage** for local settings and mission progress
- **Google Fonts · Baloo 2** for the game’s display typography

There is no framework, bundler, package manager, or backend required for the current game.

## ▶️ Run locally

1. Clone or download this private repository.
2. Open `index.html` directly in a modern browser, or serve the folder with a local static server such as VS Code Live Server.
3. Start playing.

The deployed app is served as a static site from the repository root. There is no build step to configure.

## 📁 Repository structure

```text
Blackhole-Delivery/
├── index.html   # Complete game: markup, styles, rendering, logic, and UI
└── README.md    # Project overview, gameplay guide, and rights notice
```

## 💾 Save data & privacy

Game settings and progress are saved in your browser using **Local Storage**. That means progress is tied to the browser and device you play on; it is not a cloud save and will not automatically transfer between devices. Clearing site data may remove it.

The game loads the **Baloo 2** font from Google Fonts when a network connection is available. Apart from that external font request, the game does not require a server-side game backend.

## ☄️ Deployment

The game is configured for static hosting on Vercel. The production deployment follows the repository’s `main` branch when Git integration is active.

<div align="center">

<a href="https://blackhole-delivery.vercel.app">
  <img src="https://img.shields.io/badge/OPEN%20THE%20PORTAL-PLAY%20NOW-ff4fa3?style=for-the-badge&logo=vercel&logoColor=white" alt="Open the live game" />
</a>

<sub>Built for the browser. Tuned for chaos. Delivered by Beura Labs.</sub>

</div>

---

## © Proprietary project · All rights reserved

**Blackhole Delivery** and its source code are proprietary to **Satyajit Beura / Beura Labs**. This repository does **not** include an open-source license. No permission is granted by publication or repository access to copy, redistribute, modify, republish, sublicense, or create derivative works from the code or associated project materials without prior written authorization from the rights holder.

Please do not add an open-source license or redistribute this project without explicit authorization.

<div align="center">
  <sub>© 2026 Satyajit Beura · Beura Labs. All rights reserved.</sub>
</div>
