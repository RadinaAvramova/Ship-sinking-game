# Ship Sinkingm Game 
Welcome to the Ship-Sinking-Game project! This project is a console-based game implemented in C++, simulating a naval battle where players aim to sink each other's ships by guessing their coordinates on a grid. With this game, players can enjoy a classic strategy game while honing their skills in tactical thinking and decision-making.

## Features
1. **Grid-Based Gameplay:** Utilizes a grid-based game board where players place their ships and make guesses to target opponent's ships.

2. **Ship Placement:** Allows players to strategically place their ships on the game board before the start of the game.

3. **Turn-Based Gameplay:** Implements turn-based gameplay where players take turns guessing coordinates to target opponent's ships.

4. **Feedback Mechanism:** Provides feedback to players after each guess, indicating whether the guess was a hit or a miss, and if a ship has been sunk.

5. **Game Progress Tracking:** Tracks the progress of the game, including the status of each player's ships and the number of turns taken.

6. **Win Condition:** Determines the winner of the game based on who sinks all opponent's ships first.

## Installation
To set up the Ship-Sinking-Game:

1. **Clone the Repository:** Clone the repository to your local machine using the following command:

git clone https://github.com/RadinaAvramova/Ship-sinking-game.git

2. **Navigate to the Directory:** Change your current directory to the location of the cloned repository:

cd Ship-sinking-game

3. **Compile the Code:** Compile the C++ source files using a C++ compiler (e.g., g++, clang++):

g++ -o ship_game main.cpp game.cpp player.cpp board.cpp

4. **Run the Game:** Execute the compiled executable file to start the game:

./ship_game

## Usage
1. **Game Setup:** Players set up their ships by placing them on the game board. Each ship occupies a certain number of grid cells horizontally or vertically.

2. **Gameplay:** Players take turns guessing coordinates on the opponent's game board to target their ships. Players receive feedback after each guess, indicating whether it was a hit, a miss, or if a ship has been sunk.

3. **Win Condition:** The game continues until one player sinks all of the opponent's ships. The player who sinks all opponent's ships first wins the game.

## Customization
1. **Board Size:** Customize the size of the game board by adjusting the number of rows and columns to fit different gameplay preferences.

2. **Ship Types and Sizes:** Modify the types and sizes of ships available in the game to introduce variety and challenge.

3. **Graphics and UI:*8 Enhance the game with graphical elements and user interface enhancements for a more immersive gaming experience.
