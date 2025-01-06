# Minesweeper-o-Matic
## Overview
Minesweeper-o-Matic is the final project for the CS4012 module, where the objective is to develop an auto-playing implementation of the classic Minesweeper game. The project incorporates a graphical user interface built using the Threepenny GUI library and an automatic player capable of making strategic moves based on game logic.

## Game Rules
Minesweeper is a single-player logic puzzle. The rules are simple:

The game consists of a grid with hidden mines.
Players uncover cells to reveal numbers indicating how many mines are adjacent to the cell.
The goal is to clear all non-mine cells without triggering a mine.
Cells can be flagged to mark suspected mine locations.
For a more detailed explanation, refer to the Wikipedia page on Minesweeper.

## Project Phases
### Phase 1: Basic Minesweeper Implementation
#### Objective: Model the Minesweeper game in Haskell without UI/interaction.
#### Requirements:
Randomly distribute mines across the grid.
Allow users to:
Uncover cells interactively.
Flag suspected mine locations.
Detect game-end conditions (win/loss).

### Phase 2: Automatic Player
#### Objective: Enhance the game with an auto-player.
#### Features:
Add a "Play Move" button to play safe moves automatically.
If no unambiguous safe moves are available:
Optionally play the least risky move based on probabilities.
### Challenges:
Minesweeper is NP-complete, making the creation of an efficient solver difficult.
Advanced tactics and strategies are encouraged but not required for full marks.
Grading Criteria
The project contributes 35% of the final grade for CS4012:

### Documentation (15%):
Provide detailed comments in the code.
Submit a 2–3 page design document including:
High-level design choices.
Reflection on the development process.
Evaluation of Haskell as a language for this project.
##### Basic Implementation (50%):
A well-designed, functional Minesweeper game with clear comments and documentation.
Auto-Player (35%):
At a minimum, the player should make simple and obvious moves.
Implement advanced tactics for higher marks.
### Submission Guidelines
Submit a zip file containing the project directory:
Should be a ready-to-build Stack project.
Include the documentation in the directory or as a separate file.
### Deadline: Submit by end of day, 13th December. No extensions are possible.
### Resources
For guidance and inspiration:

Richard Kaye's discussion on Minesweeper NP-completeness.
Hackaday project with Minesweeper strategies.
Minesweeper Wiki.
Sean Barrett's Minesweeper probability discussion.
Raphaël Collet's paper on solving Minesweeper with constraints.
Haskell Minesweeper package on Hackage.
