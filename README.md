# Matrix Runner 3D

An action-packed, retro-inspired 3D endless runner built entirely in the browser using **Three.js** and the **Web Audio API**. Dodge incoming obstacles, shoot down waves of biological alien monsters, and test your reflexes as the speed progressively accelerates!

## 🚀 Play the Game
[INSERT YOUR LIVE VERCEL LINK HERE]

---

## 🛠️ How It Was Built (The Tech Stack & AI Workflow)

This project was developed through a unique collaboration utilizing advanced AI sandboxes and asset generation tools:

* **Core Engine (Google Anti-Gravity):** The game's entire structure, Three.js 3D rendering pipeline, coordinate mathematics, collision detection loops, and game-state management were developed sequentially inside the Google Anti-Gravity AI sandbox. 
* **Asset Creation (Gemini):** The high-quality visual assets—including the player's sleek green/charcoal futuristic US fighter jet and the grotesque, multi-toothed, veined eyeball alien monsters—were conceptualized and generated using Gemini.
* **Audio Engineering (Web Audio API):** To avoid heavy external audio file dependencies, all retro arcade sound effects (laser fire, alien explosions, and game-over screens) were synthetically generated on the fly using raw code and the browser's native Web Audio API.

---

## 🎮 Game Features

* **3D Perspective & Environment:** A custom 3rd-person, over-the-shoulder camera view tracking a fighter jet over an infinite, glowing green Matrix-style vector grid fading into a deep black void.
* **Advanced Asset Texturing:** Fully integrated local image assets (`jet.png` and `alien.png`) utilizing alpha transparency channels and responsive billboard tracking so the enemies always face the player.
* **Dynamic Hovering Glows:** Oncoming enemies feature a soft, hovering neon aura powered by additive canvas blending. The aura dynamically flashes an angry neon red upon taking damage as a visual hit indicator.
* **Arcade Combat Loop:** Features a responsive laser-firing system with collision physics to blast enemies out of the sky for bonus points, complete with a satisfying particle explosion effect.
* **Health & Progression System:** Players start with a 3-lives buffer accompanied by a brief invincibility cooldown period after getting hit, making the game highly competitive as the speed increases over time.

---

## 🕹️ How to Play

### Objective
Survive as long as possible, shoot down the oncoming alien horde, and rack up the highest score before running out of lives.

### Controls
* **Move Left / Right:** Press the `A` / `D` keys (or Left / Right Arrow keys) to steer your jet across the grid.
* **Shoot Laser:** Press the `Spacebar` to fire a Matrix-green laser beam from your wing hardpoints.
* **Restart Game:** If you lose all 3 lives and hit the Game Over screen, press the `R` key to instantly reboot and try again.

---

## 📂 Local Setup & Installation

If you want to run this project locally or make your own modifications:

1. Clone this repository to your machine:
   ```
   git clone [https://github.com/YOUR-USERNAME/matrix-runner-3d.git](https://github.com/YOUR-USERNAME/matrix-runner-3d.git)
   ```

2. Ensure your project folder structure is maintained so the assets load correctly:

```
├── index.html
└── assets/
    ├── jet.png
    └── alien.png
```

3. Open index.html in any modern web browser to play!

(Note: If your browser blocks the asset textures locally due to CORS security policies, deploy the folder directly to Vercel or run a simple local server using Python python -m http.server or the VS Code Live Server extension).
   
