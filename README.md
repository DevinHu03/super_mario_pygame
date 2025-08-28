# Super Mario-like Game with Pygame

This is a Super Mario-like platformer game implemented using Python and Pygame. The game features player movement, jumping, enemies, collectible coins, and 4 progressively challenging levels.

## Features
- Player character that can run and jump
- Platform-based levels with ground and platforms
- Enemies to avoid
- Collectible coins for scoring
- Goal flag to complete levels
- Score tracking
- Lives system
- 4 progressively challenging levels
- Custom sprites for all game elements
- Themed backgrounds for each level

## Requirements
- Python 3.x
- Pygame library

## Installation

1. Make sure you have Python installed (the game was tested with Python 3.9.9)
2. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

## Running the Game

Navigate to the game directory and run:
```
python level_game.py
```

## Controls
- Left Arrow: Move left
- Right Arrow: Move right
- Space: Jump
- R: Reset level

## Game Elements
- Player character: Detailed red figure with hat and clothes
- Platforms: Themed platforms (grass, stone, ice, lava)
- Coins: Shiny gold coins with dollar signs
- Enemies: Themed enemies for each level (goomba, koopa, ice, fire)
- Goal: Red flag on a pole

## Levels
1. **Level 1 - Grassland**: Beginner level with basic platforms and few enemies
2. **Level 2 - Cave**: Intermediate level with more platforms and enemies
3. **Level 3 - Ice World**: Advanced level with more complex platforming
4. **Level 4 - Lava World**: Expert level with the most challenging layout

## Game Mechanics
1. Navigate the player through each level
2. Collect coins for points
3. Avoid enemies or you'll lose a life
4. Reach the goal to complete the level
5. Complete all 4 levels to win the game
6. Press R to reset the current level

## Implementation Details
The game uses Pygame sprites and groups for efficient rendering and collision detection. Physics include gravity, jumping, and collision detection with platforms. The game loop handles user input, updates game state, and renders the display at 60 FPS.

## Project Structure
- `level_game.py`: Main game file with level progression
- `level_data.py`: Level configuration data
- `create_modern_assets.py`: Script to generate modern game assets
- `requirements.txt`: Lists the required Python packages
- `modern_assets/`: Directory containing all modern game sprites

## Creating an Executable

To create a standalone executable for Windows:

1. Install pyinstaller:
   ```
   pip install pyinstaller
   ```

2. Run the packaging command:
   ```
   pyinstaller --onefile level_game.py
   ```

3. The executable will be created in the `dist` folder

