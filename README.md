# INST326_2025_FALL_THE_PIT

### Purpose of each file in our repository:
- exercise_collaborative_programming
    - This file was the introductory group assignment to ensure all group members knew the basics of how to clone the repository, commit changes, and pull updated files. This file just has our practice and does not have any code of our final Mancala game.
- interim_deliverable
    - This file is where our group implemented the Mancala game code. It contains different functions from each group member which all contributed to a fully functioning Mancala game.

### Instructions on how to run our program from the command line on MacOS
1. Open VSCode
2. Change the directory to the folder where the game file lives
3. Run it using
- python3 interim_deliverable.py
4. No required arguments, but there are two optional arguments, amount of stones (integer) and names of player(s) (string)
- If you want to include a specific amount of stones using -s or --stones, otherwise, default will be 4
- If you want to include a specific names for player1 and/or player2 using -n or --names, otherwise, default will be Player 1 and Player 2
5. Follow the instructions and enjoy the game!

### Instructions on how to use your program and/or interpret the output of the program
- When the game begins, the user will see\
Lets Play Mancala\
Player 1 vs. Player 2\
Each pit starts with 4 stones
- The game will then randomly choose which player goes first, display the game board, and tell the user which pits they can select from
- If any players select a pit that is empty or not their pit, they will receive an error message that says "You cannot choose this pit, choose one of yours"
- Once the player choose a pit, the stones from that pit will be distributed counterclockwise including their own score pit but the opponents score pit
- If the stone lands in an empty pit on their respective side, the player will capture that stone and the stones directly across into their score pit
- If the last stone lands in the players score pit, they will receive another turn
- Then players will switch turns until any players side is empty
- When the game ends, the players will see the message\
The game is over! collecting the remaining stones...
- The final message shown are the final scores, the winner, and the final game board

### Annotated Bibliography:
We didn't use any outside resources.

### Attribution Table:

| Method/Function | Primary Author | Techniques Demonstrated |
|-----------------|----------------|-------------------------|
| def check_turn()             | Jasmin Robles    | f-strings containing expressions                  |
| def parse_args(arglist)      | Jasmin Robles    | The ArgumentParser class from the argparse module |
| def get_pit_index()          | Jasmin Robles    |                                                   |
| def set_turn()               | Jasmin Robles    |                                                   |
| def display_board()          | Akbar Sajjad     |                                                   |
| def distribute()             | Akbar Sajjad     | Conditional expressions                           |
| def main()                   | Akbar Sajjad     | Composition of two custom classes                 |
| def run_game()               | Akbar Sajjad     |                                                   |
| def capture()                | Robsan Melaku    | Magic methods                                     |
| def check_move()             | Robsan Melaku    | Set operations                                    |
| def check_game_end()         | Theophilus Marfo | Comprehensions or generator expressions           |
| def calculate_final_score()  | Theophilus Marfo |                                                   |
| def check_remeining_pebbles()| Theophilus Marfo | Set operations                                    |
