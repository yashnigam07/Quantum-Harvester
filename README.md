# Quantum Harvester

A responsive, touch-optimized space shooter game where players navigate a ship using a virtual joystick, shoot with a tap button, and collect quantum cores to survive across sectors, featuring a neon aesthetic and audio effects.

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
Quantum Harvester is a single-player arcade game originally created by [yashnigam07](https://github.com/yashnigam07), enhanced with touch-only controls and responsive design. Players pilot a ship to collect green quantum cores for credits while dodging or destroying purple/orange drones. The game increases in difficulty across sectors until the player's shields are depleted.

## Features
- Touch-only controls for phones: virtual joystick for movement, tap button for shooting.
- Responsive design optimized for phones, tablets, and desktops.
- Neon aesthetic with particle effects and a sci-fi soundtrack.
- Power-ups: speed boost, shield, rapid fire, and spread shot.
- High score tracking using `localStorage`.

## Live Demo
Try the game live here: [https://yashnigam07.github.io/Quantum-Harvester/](https://yashnigam07.github.io/Quantum-Harvester/)

## How to Play
- **Objective**: Collect quantum cores (green circles) for credits, avoid or shoot drones (purple/orange triangles), and survive through sectors.
- **Power-Ups** (5-second duration):
  - **Speed (Blue)**: Increases movement speed.
  - **Shield (Yellow)**: Makes the ship invulnerable.
  - **Rapid Fire (Magenta)**: Faster shooting.
  - **Spread Shot (Green)**: Fires three lasers per shot.
- **Game Over**: Ends when shields reach zero. Final score is credits × sector.

## Setup Instructions
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yashnigam07/Quantum-Harvester.git
   ```
2. **Open the Game**:
   - Navigate to the cloned folder and open `quantum-harvester.html` in a modern browser (e.g., Chrome, Safari, Firefox).
   - On a phone: Transfer the file to your device (e.g., via USB or cloud service) and open it in your browser.
3. **Play**:
   - Tap "Launch" to start.
   - Use the touch controls (joystick and shoot button) to play.
   - Tap "Retry" to restart after game over.

## Controls
### Phone (Touch-Only)
- **Movement**: Touch and drag the bottom-left joystick to move the ship.
- **Shooting**: Tap and hold the bottom-right shoot button to fire lasers.
- **Pause**: Tap the ⏸️ button (top-right) to pause/resume.
- **Start/Restart**: Tap "Launch" or "Retry" on the respective screens.

### Desktop (Optional, if keyboard available)
- **Movement**: Arrow keys (Left, Right, Up, Down).
- **Shooting**: Spacebar.
- **Pause**: Click the ⏸️ button.

## Technical Details
- **Built With**: HTML5 Canvas, JavaScript, CSS.
- **Structure**: Object-oriented JavaScript using a `Game` class for logic, rendering, and touch handling.
- **Audio**: Background music and sound effects (hosted externally).
- **Storage**: High scores saved in `localStorage`.
- **Responsive Design**: Scales with media queries for screens below 600px.

## Troubleshooting
- **Controls Not Responding**: Ensure you’re touching within the joystick/shoot button areas. Try a different browser if issues persist.
- **Game Not Loading**: Verify the file extension is `.html` and your browser allows local file access.
- **Audio Issues**: Tap the screen to start if autoplay is blocked. Ensure an internet connection for audio files.
- **Performance Lag**: On older devices, reduce spawn rates in the `update()` method (e.g., lower `spawnRate`).

## Contributing
Contributions are welcome! Please fork the repository and submit pull requests for enhancements or bug fixes. Open issues for bugs or feature requests.

## License
© 2025 yashnigam07 - All Rights Reserved.

## Acknowledgements
- Original concept and code by [yashnigam07](https://github.com/yashnigam07).
- Enhanced with touch controls and optimizations by Grok 3 (xAI).
- Audio assets sourced from [SoundHelix](https://www.soundhelix.com) and [MyInstants](https://www.myinstants.com).

---

### How to Update the README in Your Repository
Since this is your repository, you can update the `README.md` file as follows:

1. **Edit on GitHub**:
   - Go to [https://github.com/yashnigam07/Quantum-Harvester](https://github.com/yashnigam07/Quantum-Harvester).
   - Open the `README.md` file.
   - Click the pencil icon to edit.
   - Replace the existing content with the above README.
   - Commit the changes with a message like "Update README with latest details and live demo link."

2. **Edit Locally**:
   - Open your local clone of the repository.
   - Replace the content of `README.md` with the above.
   - Commit and push:
     ```bash
     git add README.md
     git commit -m "Update README with latest details and live demo link"
     git push origin main
     ```
