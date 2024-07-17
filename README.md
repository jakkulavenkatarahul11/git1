# git1
# Number Guessing Game

Welcome to the Number Guessing Game! This is a simple console-based game where players try to guess a randomly generated number within a specified range. The game provides hints and reduces the score for each incorrect guess. The player with the highest score wins, and in case of a tie, the player with the lower age wins.

## How to Play

1. **Start the Game**: When you run the game, you'll be prompted to enter the number of players and their names.
2. **Set the Range**: The first player will set the lower and upper limits for the number range.
3. **Guess the Number**: Each player will take turns to guess the number. You will have a limited number of attempts, and for each incorrect guess, you will receive a hint and lose points.
4. **Hints**: The game will provide various hints after each incorrect guess to help you guess the number.
5. **Score**: The score starts at 100 and decreases by 10 for each incorrect guess.
6. **Winning**: The player with the highest score wins. In case of a tie, the player with the lower age wins.

## Running the Game

To run the game, simply execute the Python script. Ensure you have Python installed on your machine.

```bash
python number_guessing_game.py

Game Flow
1.The game starts by asking for the number of players and their names.
2.Players take turns guessing the number within the specified range.
3.For each incorrect guess, the game provides hints and decreases the score.
4.The game ends when all players have taken their turns, and the winner is announced.

Example
GAME STARTS
How many players are there? 2
Enter the name of player 1: Alice
 Enter your age :25
Enter the name of player 2: Bob
 Enter your age :30
Hey! Alice give the Range (Upper and lower limits )
10 50
I'm thinking of a number between 10 and 50.
Done with thinking :)
Guess the number between the range  10  to  50 :
20
Invalid input, please enter a number between 10 and 50.
Functions
get_players(): Gets the number of players and their names.
taking_range(player, i): Takes the range of numbers from the first player and generates a random number.
checkrange(m, n): Checks and swaps the range if necessary.
num_age(): Gets the age of each player.
dictionary(player, score, i): Updates the score dictionary with the player's score and age.
check_winners(): Determines the winner based on the highest score and age.
is_prime(n): Checks if a number is prime.
game(score, player, i): The main game function where players guess the number.
game_Starts(): Starts the game and manages the game flow.
Note
Ensure you enter valid numeric inputs when prompted.
Follow the prompts and hints to improve your chances of guessing the correct number.
Enjoy the game!

License
This project is licensed under the MIT License. See the LICENSE file for more details.
