# Python Hangman Project

The objective of our project is to implement the hangman game using Python. 
It doesn’t require any specific modules other than random and time. 
Python loops and functions are enough to build this game here.

## Code Explanation:

1.If the letter is correctly guessed, index searches for that letter in the word.

2. Display adds that letter in the given space according to its index or where it belongs in the given word.

3. If we have already guessed the correct letter before and we guess it again, It tells the user to try again and does not lessen any chances.

4. If the user guessed the wrong letter, the hangman starts to appear which also tells us how many guesses are left. 

5. Count was initialized to zero and so with every wrong guess its value increases with one.

6. Limit is set to 5 and so (limit- count) is the guesses left for the user with every wrong input. 

7. If it reaches the limit, the game ends, showing the right guesses (if any) and the word that was supposed to be guessed.

8. If the word is guessed correctly, matching the length of the display argument, the user has won the game.

9. Play_loop asks the user to play the game again or exit.

10. Main() and hangman() would start again if the play_loop executes to yes.

## Output

![image](https://user-images.githubusercontent.com/60151306/179450248-676b7d74-7f9b-4954-bdd4-32e35257b1c2.png)
