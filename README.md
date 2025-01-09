# Aim Trainer

This is a simple **Aim Trainer** game built with Python using the **pygame** library. The goal of the game is to improve your aiming skills by clicking on moving targets that appear on the screen. Each time you hit a target, you score a point. If you miss too many targets, the game ends. The game tracks your accuracy, speed, and other stats.

## Features

- **Dynamic Target Generation**: Targets appear at random positions on the screen and grow/shrink as they move.
- **Tracking Stats**: Tracks time, speed, accuracy, hits, and lives remaining.
- **Interactive Interface**: Displays a top bar with real-time stats and an end screen with detailed game statistics.
- **Sound Effects**: Sound is played when you hit a target.
- **Customizable Settings**: You can modify the size of the target, time intervals, and other parameters.

## Installation

### Prerequisites
- Python 3.x
- pygame library

### Install pygame

To run this project, you need to install the **pygame** library. You can install it using pip:

```bash
pip install pygame
```
Running the Game
1. Clone the repository or download the project files to your local machine.
2. Ensure you have Python 3.x installed.
3. Open a terminal or command prompt.
4. Navigate to the project folder.
5. Run the game with the following command:
```bash
pip install pygame
```
## Code Overview

### Main Features
- **Target Class**: Handles the creation, update, and collision detection of targets.
- **Game Loop**: Controls the overall flow of the game, such as target creation, collision detection, and UI updates.
- **Top Bar**: Displays real-time information like time, hits, speed, and lives.
- **End Screen**: Displays the final stats when the game ends.

### Key Variables
- **WIDTH, HEIGHT**: The dimensions of the game window.
- **LIVES**: Number of lives the player has before the game ends.
- **TARGET_INCREMENT**: The time interval (in milliseconds) for creating new targets.

### Functions
- **draw_top_bar()**: Draws the top bar with stats like time, speed, hits, and lives.
- **end_screen()**: Displays the end screen with the final results such as time, speed, hits, and accuracy.
- **collide()**: Checks if the player clicked inside a target's radius.

### Customizing the Game
- You can change the **target size**, **growth rate**, and other parameters in the `Target` class to adjust the difficulty.
- You can change the **background color** by modifying the `BG_COLOR` variable.
- Customize the **font style** and **size** by editing the `LABEL_FONT`.

## Contributing
Feel free to fork this repository, submit issues, and create pull requests if you want to add new features or improve the game.

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.
