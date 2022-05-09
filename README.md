# Wordle-Clone

Wordle

Working of wordle: It is a web application game where we have to guess a five-letter word in six guesses (Number of guesses can be altered by making few changes in the code). If any letter is present in both (Guessed word and Actual Word) the words then it is marked as yellow and if it is also at its correct position in actual word then it is marked as green. If we succeed to guess the word in six guesses, then a toast message will be displayed.

Implementation:

i. HTML:

•	Created rowS of five boxes which will contain the five-letter word.

•	Description Box- Displaying rules for the game
ii. CSS:

•	Did the styling part for the different classes we made in html file

iii. Script.js:

•	Contains the work flow of the entire application
•	Function such as:

    1.	presskey- inserting letter in boxes by keyboard and clicks on the screen keyboard
    2.	deletekey- delete the last letter inserted
    3.	fliptyle- compares the guessed and actual word and marks the words as 
      yellow- present in both but guessed position is not correct 
      grey- not present in both the words
      green- present in both at the same position
   
  
•	Event Listeners for keyboard keys and mouse clicks
•	Randomly selected a word (used Math.Random function) from the array  which contains the five letter words.
Running the Code:

Use Live Server (Extension for VS Code) or you can directly open the index.html file in any browser.
