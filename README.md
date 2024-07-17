# Pong Game

This is a simple implementation of the classic Pong game using Java and Swing. The game includes two paddles and a ball, with basic collision detection and scoring.

## Classes

The project includes the following classes:

1. **Ball**: Represents the ball in the game.
2. **Controls**: Displays the controls for the game.
3. **GameFrame**: The main game window.
4. **GamePanel**: The panel where the game is rendered and logic is handled.
5. **Menu**: The main menu screen.
6. **Paddle**: Represents the paddles controlled by the players.
7. **Score**: Keeps track of the scores of the players.
8. **ScoreMessage**: Displays a message when a player scores.
9. **PongGame**: The main class to start the game.

## Getting Started

### Prerequisites

- Java Development Kit (JDK) 8 or higher
- An IDE or text editor for Java development

### Running the Game

1. Clone the repository or download the source code.
2. Open the project in your IDE or text editor.
3. Compile and run the `PongGame` class.

## Controls

- **Player 1**: 
  - Move Up: `W`
  - Move Down: `S`

- **Player 2**:
  - Move Up: `Arrow Up`
  - Move Down: `Arrow Down`

- **Game Controls**:
  - Start Game: `Enter`
  - Show Controls: `P`
  - Reset Game: `R` (during gameplay)

## Game States

The game has three states:
1. **MENU**: The main menu screen.
2. **GAME**: The actual gameplay.
3. **CONTROLS**: The screen displaying game controls.

## Features

- Basic Pong gameplay with two paddles and a ball.
- Collision detection between the ball and paddles/walls.
- Score tracking for both players.
- Speed increase of the ball upon collision with paddles.
- Display of control instructions.
- Simple menu system to start the game and view controls.

## Screenshots

<img width="1000" alt="Ekran Resmi 2024-07-17 16 01 33" src="https://github.com/user-attachments/assets/9c011a26-96f2-45d3-998a-70ff5ca6f09c">
<img width="996" alt="Ekran Resmi 2024-07-17 15 55 14" src="https://github.com/user-attachments/assets/e985dc07-6fc8-41c4-bde1-4dce939015aa">


## Future Enhancements

- Add sound effects for ball collisions and scoring.
- Implement a start screen with more detailed instructions.
- Enhance graphics and add animations.
- Add multiplayer functionality over a network.

## Contributing

Contributions are welcome! Feel free to submit a pull request or open an issue for any bugs or feature requests.

## Acknowledgments

- The classic Pong game for inspiration.
- Java Swing documentation for guidance on UI components.

---

Enjoy playing the Pong game! If you have any questions or feedback, feel free to reach out.
