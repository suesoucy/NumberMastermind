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

**Requirements**

The following functions are required

generate_secret_number()  - No Parameters - make sure that the number has 3 unique digits (Hint: use and list of numbers, shuffle the numbers, and grab a substring

is_valid_guess(guess) - This function should just verfiy that the guess is a number and that it is 3 digits long

get_feedback(secret, guess):  -This function should receive the secret number and guess and return the results of how many numbers are in the correct position and how many are in the wrong position

**Example of returning more than one value at a time:**

**Function:**

def sampleFunc(param1, param2):
  Code
  return returnVar1, returnVar2

**Function call**

var1, var2 = sampleFunc(arg1, arg2)

var1 would contain the contents of returnVar1
var2 would contain the contents of returnVar2

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
3. 435 - 3 right spot, 0 wrong spot
