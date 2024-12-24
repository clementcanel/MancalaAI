# Mancala AI Project

This project brings the traditional Mancala game to life in a digital format, with options for two players or battles against an AI opponent. It’s designed to be both interactive and strategic, providing a great way to play and explore game theory.

## Features
- **Interactive Gameplay**: Play against another player, a random AI, or a smart AI.
- **Custom Board Options**: Players can customize the number of pits and starting stones for a more personalized game.
- **Game Logic**: Handles all aspects of the game, including valid moves, stone redistribution, capturing, and winner calculation.
- **AI Strategies**:
  - **Minimax Algorithm**: Looks ahead at possible moves and calculates the best one for the AI.
  - **Alpha-Beta Pruning**: Makes the AI faster by skipping unnecessary calculations.

## Tools and Libraries
- **Python**: The entire game is implemented in Python.
- **Libraries Used**:
  - `random`: Generates moves for the random opponent.
  - `copy`: Simulates game states during AI calculations.

## AI Performance
- The AI, powered by Minimax or Alpha-Beta pruning, dominates games against random opponents.
- **Alpha-Beta Pruning**: More efficient than Minimax and wins 98% of games in testing.
- **Game Speed**: A typical game with the AI finishes in about 0.20 seconds.

## Ideas for Improvement
- Add a graphical interface for a more engaging experience.
- Experiment with more advanced AI techniques to make the gameplay even smarter.
- Include additional rule variations for Mancala to make the game more dynamic.

## How to Run

1. **Install Jupyter Notebook**  
   Run the following command to install Jupyter Notebook:
2. **Launch Jupyter Notebook**  
Start Jupyter Notebook by running:
This will open Jupyter in your web browser.
3. **Run the Notebook**  
Open the `.ipynb` file in Jupyter and execute the cells sequentially.

