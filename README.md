# Letter Finder Function
 For this task, I've created a function called letterFinder that takes two parameters: word and match.

Inside the function:

I've implemented a 'for' loop that starts at zero, increments by 1 on each iteration, and exits when the counter variable's value is equal to the length of the word parameter.
Within the loop, there's an if statement checking if the current letter in the word (accessed using word[i]) is equal to the value of match.
If there's a match, it logs: console.log('Found the', match, 'at', i).
The else condition logs: console.log('---No match found at', i).
I've also included an example call to the letterFinder function, passing the string "test" as the word and "t" as the match.


