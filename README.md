# 🎮 Number Guessing Game in Java
This is a simple console-based number guessing game written in Java. The player tries to guess a randomly generated number within a limited number of attempts. The game is interactive, rounds-based, and gives feedback on whether the guess is too high or too low. A fun beginner-friendly project to understand control flow, user input, loops, and conditionals in Java.

🧠 Game Rules
The computer generates a random number between 1 and 100.

The player has 3 attempts to guess the number in each round.

After each incorrect guess, the game tells the player whether the guess was too high or too low.

If the player guesses correctly within the attempts, they win the round.

If all attempts are used and the number is not guessed, the correct number is revealed.

After each round, the player is asked whether they want to play again.

At the end of the session, the total number of rounds played and rounds won is displayed.

🛠️ How It Works
Key Components:
Random class is used to generate a random number between 1 and 100.

Scanner is used to take user input.

A do-while loop allows the player to keep playing rounds until they choose to exit.

if-else statements check the user guess against the generated number.

Game keeps track of:

Number of rounds played

Number of rounds won

📌 Example Output
Round 1
Guess the number between 1 and 100
Enter your guess: 45
Too low! Try again.
Enter your guess: 78
Too high! Try again.
Enter your guess: 65
Congratulations! You guessed the number correctly.
Do you want to play again? (yes/no): yes
Round 2
Guess the number between 1 and 100
...


📁 File Structure
NumberGame.java
README.md

🚀 How to Run
Clone the repository or copy the code into a file named NumberGame.java.

Compile the Java program:
javac NumberGame.java


Run the program:
java NumberGame


👶 Ideal For
Java beginners

Practice with loops and conditionals

Simple interactive game projects

Understanding basic input/output operations


