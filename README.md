# Enhanced Snake Game

This repository contains an enhanced version of the classic Snake game written in Java. The game introduces new features to make the gameplay more dynamic, engaging, and visually appealing.

## Features

- **Classic Snake Gameplay:** Navigate the snake to eat cherries and grow longer.
- **Bonus Cherries:** Occasionally spawn cherries with higher points and shorter durations.
- **Increasing Difficulty:** The snake speeds up as your score increases.
- **Pause and Resume:** Pause the game at any point and resume with a key press.
- **High Score Tracking:** Tracks your best score during the session.
- **Grid Background:** A visually appealing grid for a modern aesthetic.
- **Improved Controls:** Responsive arrow key controls for smooth gameplay.
- **Game Over Screen:** Displays your final score and provides an option to restart the game.

## Screenshots

*Add screenshots or GIFs of your game here to showcase gameplay.*

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine.

### Prerequisites

Ensure you have the following installed on your system:

- [Java Development Kit (JDK)](https://www.oracle.com/java/technologies/javase-downloads.html) 8 or later
- An IDE or text editor (e.g., IntelliJ IDEA, Eclipse, VS Code) to run the project

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/enhanced-snake-game.git
   ```

2. Navigate to the project directory:
   ```bash
   cd enhanced-snake-game
   ```

3. Open the project in your preferred IDE.

4. Compile and run the `Main` class to start the game.

### Running the Game

1. Use the arrow keys to control the snake's movement:
   - **Up Arrow**: Move up
   - **Down Arrow**: Move down
   - **Left Arrow**: Move left
   - **Right Arrow**: Move right

2. Press `P` to pause and resume the game.
3. Press `Enter` to restart after a Game Over.

## File Structure

```plaintext
src/
├── Main.java          # Entry point of the application
├── Game.java          # Main game logic and rendering
├── Snake.java         # Snake class to handle movement and growth
├── Point.java         # Point class for representing coordinates
├── GameStatus.java    # Enum to manage game states
├── Direction.java     # Enum for snake movement directions
└── cherry.png         # Cherry image used in the game (optional)
```

## Customization

Feel free to modify the game as per your preferences:

- **Cherry Appearance:** Replace `cherry.png` with a custom image in the root directory.
- **Speed and Difficulty:** Adjust `DELAY` in `Game.java` to modify the game speed.
- **Grid Size:** Update `WIDTH` and `HEIGHT` to change the game area.

## Contributing

Contributions are welcome! If you have ideas for further improvements or find any bugs, feel free to:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add your feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- The classic Snake game for inspiration.
- Java Swing and AWT libraries for GUI development.

---

Enjoy playing the Enhanced Snake Game! Feel free to share your feedback or suggest new features.
