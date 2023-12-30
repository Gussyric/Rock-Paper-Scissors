# Rock Paper Scissors Game

A simple rock, paper, scissors game implemented in Python, where you can play against the computer. The game is designed to provide a personalized experience based on your language preference and name.

## How to Play

1. Run the game script by providing your name and language preference using the command-line arguments.

   ```bash
   python rock_paper_scissors.py -n YourName -l English
   ```

   Replace "YourName" with your actual name and choose the language from English, Spanish, or German.

2. Follow the on-screen instructions to make your choice:

   - Enter `1` for Rock
   - Enter `2` for Paper
   - Enter `3` for Scissors

3. The computer will randomly choose its move.

4. The winner of the round will be announced, and the game statistics will be displayed.

5. You can choose to play another round or quit the game.

## Command-line Arguments

- `-n` or `--name`: Your name. Required.
- `-l` or `--lang`: Your language preference. Choose from English, Spanish, or German. Required.

## Game Logic

The game follows the classic rock, paper, scissors rules:

- Rock crushes Scissors
- Scissors cut Paper
- Paper covers Rock

The winner of each round is determined based on these rules. The game keeps track of the number of games played and the wins for both you and the computer.

## Play Again or Quit

After each round, you can choose to play another round by entering `Y` for Yes or quit the game by entering `Q`.

## Thank You for Playing!

Enjoy the game and have fun playing rock, paper, scissors! If you have any suggestions or feedback, feel free to let us know. Thank you for playing! 👋🎮
