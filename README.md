# Mountaineer 🏔️

An AI-generated, browser-based mountain climbing game featuring a retro ASCII-inspired visual style. Explore and navigate forests and lakes.

## 🎮 Overview

**Mountaineer** is a lightweight, first-person walking simulator built with vanilla JavaScript and the HTML5 Canvas API. It uses raycasting to create a pseudo-3D environment from a 2D tile-based world, combining classic retro aesthetics with procedural world generation.

## ✨ Features

- **First-Person Exploration** — Explore the world from a first-person perspective.
- **Retro ASCII Visuals** — Uses text glyphs, symbols, and block characters to create a distinctive visual style.
- **Natural Environments** — Features grass, forests, mountains, lakes, and other landscape elements.
- **Raycast Rendering** — Simulates 3D depth and perspective using a 2D tile-based world.
- **Interactive Controls** — Move around the environment using keyboard and mouse input.
- **Heads-Up Display (HUD)** — Displays in-game information and interface elements.
- **Minimap** — Helps players navigate and understand their surroundings.

## 🕹️ Controls

| Input | Action |
|---|---|
| `W` | Move forward |
| `S` | Move backward |
| `A` | Move left |
| `D` | Move right |
| Mouse | Look around |
| Left-click | Engage mouse controls, if required |

*Note: Controls may vary depending on the current implementation.*

## 🛠️ Tech Stack

- **HTML5** — Structures the game interface and HUD.
- **CSS3** — Styles the game screen, overlays, and interface elements.
- **Vanilla JavaScript (ES6+)** — Handles game logic, procedural generation, player movement, collision detection, and input controls.
- **HTML5 Canvas API** — Renders the environment, terrain, trees, mountains, sky, water, and minimap.
- **Unicode & ASCII-style Characters** — Creates the game's retro visual style.
- **Raycasting** — Simulates a first-person 3D perspective using a 2D tile-based world.
- **Procedural Generation** — Generates terrain and environmental features using deterministic hashing and layered noise.
- **Browser APIs** — Uses `requestAnimationFrame` for the game loop, the Pointer Lock API for mouse controls, and keyboard and mouse events for player input.

## 🚀 Getting Started

Mountaineer runs directly in a modern web browser and does not require a framework, package manager, or build process.

### Option 1: Open Directly

1. Clone or download this repository.
2. Locate `index.html`.
3. Open `index.html` in a modern web browser.
4. Start exploring!

### Option 2: Run with VS Code Live Server

1. Open the project folder in Visual Studio Code.
2. Install the **Live Server** extension if you don't already have it.
3. Right-click `index.html`.
4. Select **Open with Live Server**.

## 📁 Project Structure

```text
Mountaineer/
└── index.html    # Game interface, styling, rendering, and game logic
```

The game uses a single-file implementation, keeping the project simple to run, inspect, and modify.

## 🧠 Development Approach

Mountaineer is designed around a minimal, dependency-free architecture.

- **Single-file implementation:** HTML, CSS, and JavaScript are contained in `index.html`.
- **No external libraries:** Rendering and game mechanics are implemented using native browser technologies.
- **No build tools:** No compilation or bundling is required.
- **Procedural environments:** Terrain and scenery are generated algorithmically rather than relying entirely on pre-made maps.
- **Real-time rendering:** The game continuously updates and renders the scene using the browser's animation loop.

## 🌐 Browser Compatibility

Designed for modern desktop browsers that support HTML5 Canvas, JavaScript ES6+, and the Pointer Lock API.

For the best experience, use an up-to-date version of Firefox, Chrome, or Edge.

## 🤖 AI-Assisted Development

Mountaineer was developed 100% by AI agents (Claude and ChatGPT), with an emphasis on procedural environments, retro-inspired rendering, and lightweight browser-based gameplay.

---

**Visit Live Site** — <a href="https://elgworks.github.io/Mountaineer/">Mountaineer</a>