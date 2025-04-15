**Number Mastermind (Logic Guessing Game)**
In this game, the computer randomly selects a 3-digit number with no repeating digits. The user must try to guess the number, and after each guess, the program gives feedback:

🔁 Correct Number, Wrong Position

✅ Correct Number, Correct Position

The player continues guessing until they find the correct number. You’ll track each guess and provide a summary at the end.

🔢 Gameplay Rules:
The secret number has 3 digits, all different.

After each guess, the game returns a breakdown:

How many digits were correct and in the right position

How many digits were correct but in the wrong position

The user must keep guessing until they crack the code.

At the end, the game shows all their previous guesses with feedback.

**📘 Sample Run**

Welcome to Number Mastermind!
I have chosen a 3-digit number with no repeating digits.

Enter your guess: 123
Feedback: 1 correct number in correct position, 1 correct number in wrong position
Enter your guess: 456
Feedback: 0 correct number in correct position, 2 correct number(s) in wrong position
Enter your guess: 435
Feedback: 3 correct number(s) in correct position

You cracked the code in 3 tries!
Guess History:
1. 123 - 1 right spot, 1 wrong spot
2. 456 - 0 right spot, 2 wrong spot
3. 435 - 3 right spot, 0 wrong spot# NumberMastermind
