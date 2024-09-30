# Rock Paper Scissors Game

This is a simple **Rock, Paper, Scissors** game where a user can play against the computer. The game asks the player to input their choice, and the computer randomly selects its own. Points are awarded based on the traditional rules of Rock, Paper, Scissors:

- **Rock** beats **Scissors**
- **Scissors** beat **Paper**
- **Paper** beats **Rock**

The game is played in rounds, and you can either play again or reset the score after 5 rounds.

## Features

- User input validation ensures only valid options are accepted (rock, paper, or scissors).
- The computer selects its move randomly.
- The game automatically keeps track of the player's and computer's scores.
- After every 5 rounds, the user has the option to continue playing, reset the score, or exit the game.

## How to Play

1. **Run the script**: The game will welcome you to the Rock, Paper, Scissors game.
2. **Player Input**: You will be prompted to enter your choice:
   - `r` for rock
   - `p` for paper
   - `s` for scissors
3. The **computer makes its choice** randomly.
4. The winner is determined according to the standard rules of Rock, Paper, Scissors.
5. After 5 rounds, the score will be displayed, and you'll have the following options:
   - Press `1` to continue with your current score.
   - Press `2` to reset the score and start fresh.
   - Press `3` to exit the game.

## Example Output

```bash
Welcome to Rock Paper and Scissors game!!!
Choose either rock(r), paper(p), or scissors(s). r
The computer has chosen p
You chose r
Aww. I won.

Choose either rock(r), paper(p), or scissors(s). p
The computer has chosen s
You chose p
Aww. I won.

Good job!
Your score is: 2
My score is 3

Press 1 to continue
Press 2 to reset and continue
Press 3 to exit
