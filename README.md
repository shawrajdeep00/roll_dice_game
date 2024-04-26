# Roll Dice Game

This Python script implements a dice rolling game where players accumulate scores based on dice rolls, with the objective of reaching a specified maximum score to win the game. Players must avoid rolling a '1' to prevent their score from resetting to zero.

## Features

- **Multiple Players**: The game supports 2 to 4 players.
- **Dice Rolling**: Players roll a standard six-sided die.
- **Score Accumulation**: Players accumulate scores with each successful roll, except when rolling a '1'.
- **Score Reset**: Rolling a '1' resets the player's score to zero for that turn.
- **Winning Condition**: The first player to reach the specified maximum score wins the game.

## How to Play

1. **Setup**: Clone the repository to your local machine and ensure you have Python installed.
2. **Run the Game**: Open a terminal or command prompt, navigate to the repository directory, and run the script
3. **Gameplay**:
- Enter the number of players (2 - 4) to start the game.
- Players take turns rolling the dice by pressing 'y' when prompted.
- Each roll adds to the player's score unless a '1' is rolled, resetting the score for that turn.
- The game continues until one player reaches the maximum score.

## Customize the Game

You can customize the following parameters in the script to tailor the game to your preferences:

- `max_score`: Adjust the maximum score required for a player to win.
- `min_value` and `max_value`: Modify the range of values for the dice rolls.

## Example Gameplay

Here's an example of how the game progresses:

- Player 1 rolls a '3', adding to their score.
- Player 2 rolls a '6', adding to their score.
- Player 3 rolls a '1', resetting their score for that turn.
- Player 4 rolls a '4', adding to their score.

The game continues until one player reaches the maximum score and is declared the winner.

## Conclusion

This is a basic roll dice game, in which conditonal operators and break cases has been implemented for a basic scoring system in which either the maximum score is reached or score is reset due to occurence if any particular value.
Researchers are requested to contribute to the project in following ways - 
- Submitting bug reports or feature requests via GitHub issues.
- Forking the repository, making changes, and submitting pull requests.
- Using this block of code in their own respective projects as per their project needs.

Thank you.
