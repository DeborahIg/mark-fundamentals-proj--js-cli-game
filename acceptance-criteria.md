the user chooses to play the game
the game starts with the user having 3 lives and a score of 0. Categories are created.
the intro is displayed
while the user still has more than one life and hasn't finished the game (can still choose from categories):
the player is asked to choose a category. If the choice is not recognised, the user is prompted to choose again from given category options.
when the player chooses a valid category, that category is deleted from the dictionary and the user plays their chosen category
the user plays their chosen category:
a word is randomly selected by the computer from the chosen category and jumbles its letters
the word is removed from the category
the computer prints: What {word} is this? and prints the jumbled word
when the word is guessed correctly, the lives remain the same and the computer prints "Right!" and prints a statement wiht user's score and remaining lives
when the word is guessed incorrectly, users lose a life and the computer tells them they are wrong and offers a clue. It also prints out a statement informing users of how many lives they have left
if the user accepts a clue, the computer prints the first letter of the word
if the user still inputs the wrong answer, the computer makes fun of them
if the user does not accept a clue, they can continue to write in an answer
if the user reaches the end of the category and still have lives remaining, they are prompted to choose another category and the process starts again.
if the user still has lives and reaches the end of all the categories, they get a congratulatory message + final score + lives remaining are displayed
if the user has no lives left, it is game over + final score + lives remaining are displayed
