# Quantum Harvester

A touch-optimized space shooter where players pilot a neon-styled ship, collect quantum cores, and battle enemy drones across increasing difficulty levels.

![Quantum Harvester](path-to-your-screenshot.jpg)

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Live Demo](#live-demo)
- [How to Play](#how-to-play)
- [Setup Instructions](#setup-instructions)
- [Controls](#controls)
- [Technical Details](#technical-details)
- [Troubleshooting](#troubleshooting)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Overview
Quantum Harvester, created by [Yash Nigam](https://github.com/yashnigam07), is an arcade-style game where players collect quantum cores while avoiding or destroying enemy drones. As players progress, difficulty increases, testing their reflexes and strategy.

## Features
- **Touch-based controls**: Virtual joystick for movement, tap button for shooting.
- **Neon aesthetics**: Stunning visual effects and dynamic particle animations.
- **Power-ups**: Speed boost, shield, rapid fire, and spread shot.
- **High score tracking**: Saves best scores using `localStorage`.
- **Adaptive design**: Optimized for mobile, tablet, and desktop.

## Live Demo
Play now: [Quantum Harvester](https://yashnigam07.github.io/Quantum-Harvester/)

## How to Play
- **Objective**: Collect **green quantum cores** while evading or destroying **enemy drones**.
- **Power-Ups (5s duration):**
  - **Speed (Blue)**: Boosts movement speed.
  - **Shield (Yellow)**: Grants temporary invincibility.
  - **Rapid Fire (Magenta)**: Enhances firing speed.
  - **Spread Shot (Green)**: Shoots three lasers at once.
- **Game Over**: Shields deplete, ending the run. Final score = credits × sector.

![Gameplay](SS.png)

## Setup Instructions
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yashnigam07/Quantum-Harvester.git
   ```
2. **Run the Game**:
   - Open `index.html` in a modern browser.
   - On mobile, transfer and open the file in a browser.
3. **Start Playing**:
   - Tap "Launch" to begin.
   - Control the ship using the joystick and fire button.
   - Tap "Retry" to restart after game over.

## Controls
### Mobile (Touch-Only)
- **Move**: Drag the bottom-left joystick.
- **Shoot**: Tap and hold the bottom-right fire button.
- **Pause**: Tap ⏸️ (top-right corner).
- **Start/Restart**: Tap "Launch" or "Retry".

### Desktop (Optional Keyboard Support)
- **Move**: Arrow keys.
- **Shoot**: Spacebar.
- **Pause**: Click ⏸️ button.

## Technical Details
- **Built with**: HTML5 Canvas, JavaScript, CSS.
- **Game Structure**: Object-oriented JavaScript design.
- **Audio**: Background music and sound effects.
- **Storage**: High scores saved in `localStorage`.
- **Responsiveness**: Scales dynamically for various screen sizes.

## Troubleshooting
- **Unresponsive Controls**: Ensure correct touch input. Try a different browser if needed.
- **Game Not Loading**: Verify file extension and browser permissions.
- **No Audio**: Tap screen to enable sound if autoplay is blocked.
- **Performance Issues**: Adjust `spawnRate` in `update()` for better performance on older devices.

## Contributing
We welcome contributions! Fork the repo, submit pull requests, or open issues for improvements.

## License
© 2025 Yash Nigam - All Rights Reserved.

## Acknowledgements
- **Concept & Code**: [Yash Nigam](https://github.com/yashnigam07)
- **Audio Assets**: [SoundHelix](https://www.soundhelix.com), [MyInstants](https://www.myinstants.com)


