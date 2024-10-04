# Snake Game

Welcome to the **Snake Game**, a classic arcade game implemented in Java using Swing. The goal of the game is to control a snake that grows longer as it eats cherries, while avoiding collisions with the walls and the snake's own tail.

## Features

- Classic Snake gameplay mechanics
- Cherry spawning and eating system
- Score tracking with best score saving
- Game pause and resume functionality
- Game over condition handling
- Simple and intuitive controls
- Colorful graphics with a cherry image (customizable)

## Getting Started

### Prerequisites

To run this project, ensure you have the following installed:

- Java Development Kit (JDK) 8 or higher
- An IDE (such as IntelliJ IDEA, Eclipse, or NetBeans) or a text editor
- [Optional] The `cherry.png` image file (included in the repository)

### Clone the Repository

To get started, clone the repository to your local machine:

bash
git clone https://github.com/your-username/snake-game.git
### Compile and Run

1. Open the project in your IDE or navigate to the project directory in your terminal.
2. Compile the Java files. If using the command line, you can compile the files with:

   ```bash
   javac Main.java
### Controls

- **Arrow Keys**: Control the direction of the snake (Up, Down, Left, Right)
- **P**: Pause or resume the game
- **Enter**: Restart the game after a game over

### Game Logic

- The snake moves automatically in the direction it is facing.
- The player can change the snake's direction using the arrow keys.
- Each time the snake eats a cherry, it grows longer, and the score increases.
- The game ends if the snake collides with the walls or itself.
- The best score is saved and displayed during the game.

### Customization

- You can replace the default cherry image (`cherry.png`) with your own by placing an image file named `cherry.png` in the project directory.
- Modify the game settings, such as the width, height, and delay, by changing the constants defined in the `Game` class.

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### Acknowledgments

- Inspired by the classic Snake game and tutorials on game development with Java.
- Thanks to the open-source community for various resources and libraries that made this project possible.
