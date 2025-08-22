# Vampire Shooter Game

- A 2D top-down vampire shooter game built using **Pygame** and **PyTMX**.  
- Dodge, shoot, and survive waves of enemies in a tile-based map rendered from TMX files.

## Demo

![Gameplay Demo](demo/vampire-shooter-demo.gif)

## Features

-  **Shooting Mechanics**: Aim with your mouse and shoot in real-time with cooldown and bullet lifespan.
-  **Enemy AI**: Vampires spawn dynamically and follow the player using directional vectors and collision handling.
-  **Tile-Based Map**: TMX maps loaded with PyTMX for layered level design (ground, objects, collisions, entities).
-  **Sprite Animation**: Smooth player and enemy animations based on movement direction and state.
-  **Collision Detection**: Bullet vs. enemy collisions and wall obstruction handling.
-  **Audio System**: Integrated sound effects for shooting and hits, plus background music support.
-  **Modular Codebase**: Organized into separate directories for code, assets, and data to ensure scalability.

## Tech Stack

- Python
- [Pygame](https://github.com/pygame-community/pygame-ce)
- [PyTMX](https://github.com/bitcraft/PyTMX)
- Tiled Map Editor (for `.tmx` maps)

## Getting Started

1. **Install dependencies**:
   ```bash
   pip install pygame-ce pytmx
    ```
2. **Clone the repository**:
    ```bash
    git clone https://github.com/zepredos/Vampire-Shooter.git
    cd Vampire-Shooter
    ```
3. **Run the game**:
    ```bash
    python main.py
    ```

## Controls

- WASD / Arrow keys: Move player
- Mouse: Aim
- Left Click: Shoot

## Future Improvements

- Game Over screen
- Health system and score counter
- Multiple weapons and power-ups
- Save/load feature
- Improved enemy types and pathfinding
