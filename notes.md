# .Net Deliverable 2 Assignment 2

## Notes

## Task: Counting Heads or Tails
- Write a console app that takes in a word (“heads” or “tails”) and number from the user.
- The number will represent how many coin flips the program outputs.
- Repeat coin flips based on the number of flips entered by the user (use the numberOfFlips​ variable). Each time:
-- Output the result of each coin flip on its own line,
 -- Followed by:
        -the number
        -percentage of total correct guesses

## Varibles
- headsOrTailsGuess - string - input from user 
- numberOfFlips - int - Repeat coin flips based on the number of flips entered by the user - 
- correctCount - int -
- percentage - double - 

## Class
- Random Class
--  Use the R​andom ​class to generate a new number each time.


## User steps
1. users sees "Guess which will have more: heads or tails?"
2. user inputs string "heads"
3. user sees "how many times shall we flip a coin?"
4. user inputs the number 5
5. user sees head or tails 5 times on separate lines 
6. user sees "your guess, ${headsOrTailsGuess}, came up ${correctCount} times."
7. ueser sees "That's ${percentCorrect}'"

## Point BreakDown

1. Correctly gets user input from the console.
2. Stores first user input in a variable named ​headsOrTailsGuess.​
3. Stores second user input in a numeric variable named n​ n umberOfFlips​.
4. Loops the correct number of times.
5. Generates random numbers each time.
6. Correctly generates and displays a random heads or tails each time.
7. Adds to ​correctCount​ accurately.
8. Displays the user choice at the end (either heads or tails).
9. Displays the correct count at the end.
10.Displays the correct percentage at the end.

## CSharp SoSharp



## Resources
- [microsoft documentation on random class](https://docs.microsoft.com/en-us/dotnet/api/system.random?view=netcore-3.1)
var rand = new Random();

- [stack overflow suggestion Convert a ReadLine into int](https://stackoverflow.com/questions/24443827/reading-an-integer-from-user-input)
  Convert.ToInt32()



**Remember to write down questions**


