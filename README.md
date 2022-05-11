# Pro-Wordle
Project Description
The Pro-Wordle game is made up of two main phases:
(1) a knowledge base building phase and (2) a game play phase.
In the KB building phase, the player is prompted to enter words with their categories.
Corresponding facts are added to the KB using the predicate word/2 where word(W,C)
is true if W has a category of C. This continues until the player enters done. Below is a
sample of the interaction between the game and the player in the KB building phase.

Welcome to Pro-Wordle!
'----------------------'
Please enter a word and its category on separate lines:
|: horse.
|: animals.
Please enter a word and its category on separate lines:
|: panda.
|: animals.
Please enter a word and its category on separate lines:
|: hello.
|: greetings.
Please enter a word and its category on separate lines:
|: banana.
|: fruits.
Please enter a word and its category on separate lines:
|: hoard.
|: collections.
Please enter a word and its category on separate lines:
|: done.
Done building the words database...

After the KB building phase, the game play phase begins. The game displays to the user
the available categories to pick one from. The player is then prompted to pick a length
and category for the word to be guessed. The game picks a word of the given length and
category and the guessing game begins. The player is allowed a maximum number of
guesses equal to the entered length plus one. In each guess, the user must enter a word of
the chosen length. The game then displays to the user the correctly entered letters (not
necessarily in correct positions), and the correctly entered letters in correct positions.
