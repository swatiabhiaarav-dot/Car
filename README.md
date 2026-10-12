# 🏎️ Apex 3D Speed Simulator
A lightweight, browser-based 3D car racing game built with Three.js and WebGL. Features procedural vehicle modeling, responsive arcade physics, custom paint jobs, and both solo and multiplayer-style modes without requiring external model assets.
---
## 🎮 Features
* **Procedural 3D Car Models**: Switch seamlessly between GT Sport, V8 Muscle, and 4x4 Trailblazer models.
* **Full Customization**: Real-time color pickers for vehicle body paint and wheel rims.
* **Responsive Physics**: Custom arcade physics including acceleration, realistic steering angles, reverse, handbrake drifting, and rolling wheel animations.
* **Dynamic Camera**: Smooth third-person chase camera tracking.
* **Game Modes**:
  * **Offline Solo**: Free-roam time trial on a closed loop circuit.
  * **Online Lobby**: Circuit session with dynamic competitor racers.
* **HUD Display**: Integrated digital speedometer (KM/H) and game state badges.
* **Zero Asset Dependencies**: All meshes, tracks, curbs, and textures are generated procedurally via code (no external `.obj`/`.gltf` files or broken asset paths).
---
## 🕹️ Controls

| Action | Primary Key | Alternative Key |
| :--- | :--- | :--- |
| **Accelerate** | `W` | `Up Arrow (↑)` |
| **Brake / Reverse** | `S` | `Down Arrow (↓)` |
| **Steer Left** | `A` | `Left Arrow (←)` |
| **Steer Right** | `D` | `Right Arrow (→)` |
| **Handbrake / Drift** | `Space` | — |
| **Reset Car Position** | `R` | — |

---
## 🚀 Quick Start / How to Run
### Method 1: Direct File Launch (No Setup Needed)
1. Download or clone this repository.
2. Double-click `index.html` to run it directly in any modern browser (Chrome, Edge, Firefox, Safari).
### Method 2: Local Development Server (Recommended)
If you are modifying code or testing real networking extensions:
```bash
# Clone the repository
git clone [https://github.com/your-username/apex-3d-car-game.git](https://github.com/your-username/apex-3d-car-game.git)
# Navigate into project directory
cd apex-3d-car-game
# Serve using Python 3
python -m http.server 8000
# OR serve using Node.js / npx
npx serve
