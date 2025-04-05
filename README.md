# Ayoayo Game Implementation

This is a text-based implementation of the Ayoayo board game for the EA Eye Scout software developer assessment.

## Game Description

Ayoayo is a traditional African board game similar to Mancala. Players move seeds around the board with the goal of capturing more seeds than their opponent.

### Game Rules
- Each player has 6 pits with 4 seeds in each at the start
- Players take turns picking up seeds from one of their pits and distributing them counter-clockwise
- If the last seed lands in the player's store, they get another turn
- If the last seed lands in an empty pit on their side, they capture seeds from the opposite pit
- The game ends when all pits on one side are empty
- The player with the most seeds in their store wins

## Implementation

The game is implemented using three main classes:

1. **Ayoayo.java** - Main game logic class that handles:
   - Game board representation
   - Seed movement rules
   - Special rules implementation (extra turn, capturing)
   - Game end detection

2. **Player.java** - Simple class to represent a player and store their name

3. **Main.java** - Contains test cases to demonstrate the game functionality

## How to Run

1. Compile all Java files:
2. Run the Main class:
3. The program will run through test cases showing how the game works

## Implementation Approach

I decided to represent the board as a single array with 14 positions:
- Positions 0-5: Player 1's pits
- Position 6: Player 1's store
- Positions 7-12: Player 2's pits
- Position 13: Player 2's store

This design made it easier to implement the counter-clockwise movement of seeds around the board.




