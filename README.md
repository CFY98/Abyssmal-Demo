# Abyssmal (Prototype)
## 📖 Game Overview
After discovering Flint has gone missing on their archaeology expedition, Jasper must venture into the abyss to find him. Collect Batteries to replenish your Battery Life and as an archaeologist, artifacts to improve your score! Available on itch.io to play in-browser or to download as an executable (Windows Only).

## Team
> Games Developer: CFY

```
Start Demo
├── Play Game
|     Tutorial
|     ├── Levels 1–3
|     │   └── On Fail
|     │       ├── Continue
|     │       └── Bad Ending
|     └── Good Ending
|
└── Exit Game
```

## ✨ Features
![Gameplay](level1.png)
- **Character Navigation** — Via keyboard controls, the player can move the character and interact with objects such as doors, enemies, collectibles and Chalk, the NPC.
- **NPC Dialogue** — In the Tutorial, the character Chalk guides the player through the controls and the setup of the game.
- **Collision Events** — Vertical and horizontal checks to check for objects that obstruct the player's path.
- **Enemy UI** — Enemies detect and attack the player using distance-based calculations (Pythagorean theorem) to trigger combat, creating appropriate layers when within range. 
- **Timer as Healthbar** — A dynamic timer doubles as the player’s health bar. As time decreases, the environment gradually darkens, increasing tension and visual feedback.
- **Replenishing items** — Items such as batteries add an additional 30 seconds to the timer.
- **Artifact Score** — A score counter that is updated when the player interacts with a collectable.
- **Checkpoints** — New instances are created when the player continues to play the game or falls outside of the bounds of the levels. 
- **Branching Paths** — The player may upon failure, the player has the option to continue which will lead to the good ending upon completion. The second option, 'give up', shall lead to the bad ending.
- **Main Menu** — Another branching path which allows the player to start the game or end the demo.

## 🎮 Controls
- **Left Key**: Movees the player to the left.
- **Right Key**: Moves the player to the right.
- **Spacebar**: Allows the player to jump.
- **Enter**: Triggers collision event with doors.
- **Control Key**: For interactions with Chalk.

## Installation
Please see [Abyssmal Demo](https://h5h5.itch.io/abyssmal-demo)

## ⛏️ Built With
- **GameMaker**: Utilised tilemaps, objects, timers and collision events to develop the gameplay loops and UI.
- **Aseprite**: Developed the playable character, light, and collectibles spritesheets for GameMaker.
- **Additional Sources**
- `GameDevMarket` — Additional sprites, music, and background images.

## 📄 License
This project is licensed under the **MIT License**.
