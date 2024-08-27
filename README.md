# Bull-Cow Game
This is a command-line implementation of the classic "Bulls and Cows" game, where the player tries to guess a secret 4-digit number. The digits in the number are unique, and the player receives feedback after each guess in the form of "bulls" and "cows."

## How to Play
1. **Objective**: Guess the 4-digit secret number.
2. **Rules**:
   - The secret number is a 4-digit number with no repeated digits.
   - Each guess must be a 4-digit number with unique digits.
   - After each guess, you will receive:
     - **Bulls**: The number of digits that are both in the correct position and match the secret number.
     - **Cows**: The number of digits that are in the secret number but in the wrong position.
3. **Winning the Game**: You win if you correctly guess the secret number within the allowed number of tries.

## Example Gameplay
1. The game will generate a random 4-digit number (e.g., 1234).
2. You will be prompted to enter the number of tries you want.
3. You will then be asked to enter your guess.
4. The game will respond with the number of bulls and cows.
5. The game continues until you either guess the number correctly or run out of tries.

### Example Output
```plaintext
Enter number of tries: 10
Enter your guess: 1234
2 bulls, 1 cows
Enter your guess: 5678
0 bulls, 0 cows
Enter your guess: 4321
0 bulls, 4 cows
...
You guessed right!
