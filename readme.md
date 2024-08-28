# Solitaire Clone

A simple and fully functional solitaire game built with Python using the `arcade` library. This project implements a classic solitaire game with drag-and-drop functionality, flipping cards, and auto-arranging piles. The game is currently in development but will include all key solitaire features.

## Features
- **Drag and Drop**: Click and drag cards to move them between piles.
- **Automatic Shuffling**: Cards are automatically shuffled at the start of every game.
- **Card Flipping**: Click on a face-down card to flip it over.
- **Dynamic Piles**: Cards stack and fan out dynamically.
- **Restart Option**: Press `R` to restart the game at any point.
- **Animated Movements**: Smooth transitions for card movements.
  
## Gameplay
- **Objective**: Move all cards to the four top piles, sorted by suit in ascending order (from Ace to King).
- **Initial Setup**: Cards are dealt into seven piles with the top card of each pile face-up. The remaining cards are placed in a draw pile.

## Controls
- **Mouse Controls**:
  - **Click & Drag**: Select and move cards between piles.
  - **Flip Cards**: Click on face-down cards to flip them.
  - **Deck Interaction**: Click on the draw pile to reveal new cards.
- **Keyboard Controls**:
  - Press `R` to restart the game.

## Installation
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/solitaire-clone.git
   cd solitaire-clone
2. **Install Dependencies**: 
    Ensure you have Python 3.x installed and then install the required libraries:
    ```bash
    pip install arcade
3. **Run the Game**:
    ```bash
    python solitaire.py

## TBD Enhancements

1. Win Condition**: Check for game completion and display a victory message when all cards are sorted correctly.
2. Undo Feature: Allow players to undo their last move.
3. Hints: Implement hints for suggested moves.
4. Improved UI: Enhance the game's interface with a modern design.
    - Allow players to see the number of facedown cards in the mat.
5. Implement difficulty levels.

## Contributions
Feel free to contribute to this project! You can submit issues or create pull requests to improve the game. Any feedback or suggestions are welcome.

## License
N/A