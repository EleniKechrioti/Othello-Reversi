# Othello-Reversi

Othello Reversi is a java based game build with graphics for our Artificial Intelligence course at AUEB. 
Othello is a two-player game, and here the player plays against the AI, which is implemented with the Minimax algorithm using a-b pruning.
Our report for this project can be found in greek [here](https://github.com/EleniKechrioti/Othello-Reversi/blob/main/report.pdf).

## How to play
1. Clone the project.
2. Open your terminal.
3. Run
   ```sh
   >>javac *.java
   >>java Window
   ```
4. Starting screen will show up.
5. Select the turn you want to play and the difficulty level.
6. Select "Start" and enjoy!

Alternatively you can run the following commands 
  ```sh
  >>javac *.java
  >>java Main
  ```
and play on your terminal.<br>
Note: For the printing of the game board we used unicodes for coloring, so it may not be recognized from your terminal.

## Features
- Responsive AI using MinMax algorithm with alpha-beta pruning
- Customizable depth for the MinMax algorithm, selected by the user (1-5 can be visualized as difficalty level)
- Adaptable turn-user can choose if he wants to play first or second
- Possible valid moves for the user are provided, to help him play easier
- Error messages for invalid moves-checking for users miss
- Command line and GUI implementation

## Collaborators
- [Eleni Kechrioti](https://github.com/EleniKechrioti)
- [Maria Schoinaki](https://github.com/MariaSchoinaki)
- [Christos Stamoulos](https://github.com/ChristosStamoulos)

