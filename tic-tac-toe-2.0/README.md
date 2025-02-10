# Advanced Tic-Tac-Toe 2.0

## Description
This is a dynamic version of the classic Tic-Tac-Toe game developed in Python. It allows players to alter their moves until a winner is determined.

## Aim

The aim of this project is to develop an advanced Tic-Tac-Toe game for two players. In this game, players take turns placing their symbols on a 3x3 grid. The player who successfully aligns three of their symbols horizontally, vertically, or diagonally first wins the game. The game is designed to ensure there is always a winner, with no possibility of a tie.

## Features
- Two-player gameplay
- Dynamic move adjustments
- Simple, interactive command-line interface

## How to Play
1. Run the script using Python.
2. Player 1 (X) and Player 2 (O) take turns to enter the position (1-9) on the board.
3. The game ends when any one of the player wins.

## Gameplay

**Ultimate Tic-Tac-Toe** is a more complex variation of traditional Tic-Tac-Toe with added strategic depth. Unlike regular Tic-Tac-Toe, each move on a local 3x3 board affects the next possible moves on the global board. The game introduces new elements that players need to consider:

1. **Anticipating the Next Move**: Each move played on a local board determines where the opponent's next move may be played. This makes some moves, which might seem disadvantageous in normal Tic-Tac-Toe, strategically valuable since the opponent could be forced into a less favorable position.

2. **Visualizing the Game Tree**: The game tree becomes more complex as every move impacts future board positions. Predicting the outcome becomes more difficult, as each local move contributes to the larger global game board and can lead to vastly different future scenarios.

3. **Winning the Game**: The goal is to control the global board by winning local boards. Local wins alone are not enough to claim victory unless they contribute to the overall strategy of winning the global board. Sacrificing some local boards to gain more important ones is a key tactic.

## Advanced Tic-Tac-Toe 2.0

In **Advanced Tic-Tac-Toe 2.0**, the rules are further refined for an even more dynamic and engaging gameplay experience:

- **Unlimited Symbol Movement**: Unlike the traditional Tic-Tac-Toe, players can move their symbols multiple times, adding flexibility to the game and creating more strategic possibilities.
  
- **No Draws**: The game is designed in such a way that a winner is guaranteed. There will never be a tie, ensuring a definitive outcome.

## Features
- Players have the freedom to move their symbols **any number of times** during the game.
- The game is always resolved with a **guaranteed winner**—no chance of a draw.

For the **FUTURE PLANS** section of your **README.md** or **SRS.txt**, here's an improved version incorporating your goals of adding keyboard functions, more complex boards, and AI integration for your **Advanced Tic-Tac-Toe 2.0** project:

## Future Plans

### 1. **Keyboard Functionality**
In the upcoming version, we plan to add keyboard functionality to make the game more accessible and enhance the player experience. Players will be able to use keyboard shortcuts to select positions on the board, move their symbols, and navigate the game interface more efficiently.

### 2. **Complex Boards**
We aim to design and implement more complex board configurations in future updates. This could include larger boards or multi-layered boards, providing players with a deeper and more challenging gameplay experience.

### 3. **AI Integration**
A key enhancement for the future will be developing an AI opponent capable of playing the game. This will involve designing an AI that can evaluate possible moves, anticipate player strategies, and make intelligent decisions. The AI will follow a strategy based on evaluating all possible game states and choosing the optimal move. Although the AI for **Tic-Tac-Toe** is relatively simple compared to more complex games like chess, we will look into optimizing it to provide a competitive challenge for players.

### 4. **Enhanced Gameplay**
- Introducing features like difficulty levels for the AI, allowing players to choose between easy, medium, and hard levels.
- Additional rules or variants can be incorporated to make the game more dynamic and engaging.

## Summary

This project focuses on the advanced version of Tic-Tac-Toe, where the objective is to match symbols horizontally, vertically, or diagonally. The game is designed for two players who take turns to place their symbols on the board. The game continues until a player successfully aligns three symbols in a row, column, or diagonal. 

In this version, players are allowed to place their symbol in any empty position, and they are not restricted to a fixed sequence. Once a symbol is placed, the player cannot move it. The game ensures that there will always be a winner, and there will be no possibility of a tie, unlike in traditional Tic-Tac-Toe.

## Conclusion

This project, titled "Tic-Tac-Toe Genius," integrates basic artificial intelligence to provide an engaging experience. Tic-Tac-Toe is a globally recognized and simple game, but with a touch of AI, it becomes more dynamic and challenging. The game does not require complex algorithms or pseudocode, and can be easily developed using basic Python programming techniques. The core of the game revolves around finding possible combinations: horizontal, vertical, and diagonal alignments, which remain the fundamental mechanics of the game.