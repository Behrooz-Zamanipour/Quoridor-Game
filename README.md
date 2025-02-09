## Quoridor Game
This is a **team-based** C++ console game project developed collaboratively by **Behrooz Zamanipour & Amir Zarrabinia**. The game features two players (**P** and **R**) who strategically place walls and move across a grid. The objective is to reach the opposite side of the board first while blocking the opponent’s path.

## Team Members
- **Behrooz Zamanipour** – Core game logic & movement mechanics
- **Amir Zarrabinia** – Wall placement system & game UI

## How to Play

1. **Start Game**:
   - Choose option `1` to start the game.
   - The board will display player positions and available moves.

2. **Game Turns**:
   - Each player takes turns to either **Add Wall** or **Move**.
   - Players can choose between placing a **horizontal or vertical wall**, or moving **up, down, left, or right**.

3. **Objective**:
   - The first player to **reach the opponent’s starting row** wins.

## Game Controls

- **Menu Options**:
  - `1` to Start the Game.
  - `2` to Exit.

- **Player Actions**:
  - **Add Wall**:
    - Choose between **Horizontal (1)** or **Vertical (2)** placement.
  - **Move**:
    - Choose the direction: **Up (1), Down (2), Left (3), Right (4)**.

## Compilation and Execution

To compile the code, use the following command in your terminal:

```bash
g++ -o GameBoard Project.cpp
