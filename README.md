# Number_guessing_game
Hello everyone, today I will be showing you how I made a thing that can play the number guessing game.

# How to play Number guessing game
First, I will talk about the number guessing game. The number guessing game is a game where you choose a number with a certain number of digits and the number has no 0’s or repeating digits. First, someone guesses a number. If they have 1 or more digits that are in the correct position, then say how many digits are in the correct positions and say that is the number of “A’s”’. Then, if they have 1 or more digits that are in the wrong position but are still in the number, then say how much they have and say that is the number of ”B’s”. For example, if your number is 152 and they guess 123, you would say 1 A and 1 B.

# How my guesser works
Now we will talk about how my guess of the numbers work. First, it creates a list of all possible guesses to numbers. For the first guess, they will choose the first one. Then, it eliminates all the possibilities that are impossible. For example, if it guesses 123 and the hint is there is 1 B, then it will remove the possibilities that are impossible such as 456 since it does not contain any of the digits in 123 and will be impossible. 145 will also be eliminated because even though it contains 1, it is in the same position as the actual answer and one b means it should be in a different position.

# How good it is at guessing
After some analysis, it says that 1-3 digits takes about 5-6 guesses and 4-9 takes about 7-9 guesses so it slowly increases based on how many digits. But we cannot use this algorithm ourselves because its gonna take too long to list every single possible guess.

