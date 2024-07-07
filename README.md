# Rock-Paper-Scissors Game

This is a simple Rock-Paper-Scissors game implemented in HTML, CSS, and JavaScript. The game allows the user to play against the computer and keeps track of the score.

## How to Play

1. Open `Rock.html` in your web browser.
2. Click on either "Rock," "Paper," or "Scissors" buttons to make your choice.
3. The computer will randomly select its move.
4. The winner is determined based on the rules:
   - Rock beats Scissors
   - Scissors beats Paper
   - Paper beats Rock
5. Your score is updated accordingly:
   - If you win, you get 1 point.
   - If you lose, you get 0 points.

## Files

- `Rock.html`: The main HTML file containing the game interface.
- `Paper.css`: CSS file for styling the game elements.
- `Scissors.js`: JavaScript file with game logic.

## How It Works

- The game uses event listeners to capture user clicks on the buttons.
- The computer's move is randomly generated using JavaScript's `Math.random()` function.
- The winner is determined by comparing the user's choice with the computer's choice.
- The score is updated accordingly.
