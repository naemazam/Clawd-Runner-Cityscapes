# Clawd Runner: Cityscapes

<p align="center">
  <img src="https://github.com/naemazam/Clawd-Runner-Cityscapes/blob/main/assets/gamelogo.png" width="120" />
</p>

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**Clawd Runner: Cityscapes** is a modular reimagining of the classic infinite runner game ft Clawd by Claude Code. it features dynamic aesthetic themes, real-world cityscape backgrounds

<p align="center">
  <img src="https://github.com/naemazam/Clawd-Runner-Cityscapes/blob/main/assets/poster.png" width="600" />
</p>

[Play](https://naemazam.github.io/Clawd-Runner-Cityscapes/)
---
<p align="center">
  <img src="https://github.com/naemazam/Clawd-Runner-Cityscapes/blob/main/assets/1.png" width="350" />
  <img src="https://github.com/naemazam/Clawd-Runner-Cityscapes/blob/main/assets/2.png" width="350" />
</p> 

## 🎮 How to Play

### Desktop Controls

[ SPACE ] or [ UP ARROW ] : Jump

[ DOWN ARROW ] : Duck

[ ESC ] : Pause / Open System Config Menu

###  Mobile / Touch Controls

Tap Top Half of Screen : Jump

Tap Bottom Half of Screen : Duck


## ✨ Features

*   🌆 **Dynamic Aesthetics:** Switch seamlessly between **Cyberpunk**, **Sci-Fi**, **Modern**, and **Classic** themes. Each theme alters the color palette, visual filters, and shadow rendering.
*   🗺️ **Global Locations:** Run through procedurally blended vector skylines of New York City, Shanghai, Dhaka, or stick to the Classic 8-bit desert.
  
---

## 📂 Project Structure

The project has been refactored from a monolithic single-file script into a clean, scalable folder structure:

```text
Clawd-Runner-Cityscapes/
├── index.html        # Main entry point and UI layout
├── styles.css        # Theme variables and responsive styling
└── js/
    ├── state.js      # Global variables, DOM cache, and asset loading
    ├── entities.js   # Player and Obstacle classes/logic
    ├── renderer.js   # Canvas drawing, parallax backgrounds, and composition
    ├── engine.js     # Core game loop, collision detection, and spawn rates
    └── controller.js # Event listeners for keyboard, touch, and UI

```

