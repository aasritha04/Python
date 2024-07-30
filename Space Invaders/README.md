# Space Invaders

This is a simple Space Invaders game implemented using Python and Pygame. The game features a player-controlled spaceship, enemies, bullets, and sound effects.

## Features

- Player spaceship that can move left and right
- Enemies that move horizontally and descend towards the player
- Bullets that the player can fire to destroy enemies
- Score tracking
- Background music and sound effects for shooting and explosions
- Game Over screen when enemies reach the player

## Preview


## Requirements

- Python 3.7+
- Pygame

## Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/aasritha04/Python-Projects.git
    cd Python-Projects/Space Invaders
    ```

2. Create and activate a virtual environment (optional but recommended):

    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:

    ```sh
    pip install pygame
    ```

## Usage

1. Ensure you have the following assets in the `./assets` directory:
    - `background.png`
    - `background.wav`
    - `ufo.png`
    - `player.png`
    - `enemy.png`
    - `bullet.png`
    - `laser.wav`
    - `explosion.wav`

2. Run the game:

    ```sh
    python main.py
    ```

## Project Structure

- `main.py`: The main script containing the game code.
- `assets/`: Directory containing game assets (images and sounds).

## Code Explanation

The main parts of the `main.py` script:

1. **Initialization and Setup:**
    - Initialize Pygame.
    - Create the game screen.
    - Load background image and sound.
    - Set the game window caption and icon.

2. **Player Setup:**
    - Load player image.
    - Set initial player position.

3. **Enemy Setup:**
    - Load enemy image.
    - Set initial enemy positions and movements.

4. **Bullet Setup:**
    - Load bullet image.
    - Set initial bullet state and position.

5. **Score and Game Over:**
    - Initialize score and fonts for displaying text.
    - Define functions to show score and game over text.

6. **Game Loop:**
    - Handle events (key presses for movement and shooting).
    - Update player and enemy positions.
    - Check for collisions between bullets and enemies.
    - Update the screen with new positions and draw everything.

