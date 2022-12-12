# Level3Project
Project Overview
Two players (human vs. computer) each have 2 piles of tokens (one pile of black and one pile of
red). On a player’s turn (s)he will roll a black die and a red die and manipulate his or her or the
opponent’s pile of tokens based on the dice rolls. The object of the game is to get rid of all of
the black tokens and have the most red tokens.
Display
The list below includes the essential elements of the page.
● The game needs 2 sections of output, one for the player and one for the computer.
o Each section will show the number black tokens and the number of red tokens
owned by the player (this is 12 at the start of the game).
o Each section should have a display for the results of that player’s last dice roll.
● The player section will have a Roll Dice button.
● The player section will have 4 additional buttons, one for each of the player’s options.
o Add to your red pile and remove from your opponent’s black pile.
o Add to your black pile and remove from your opponent’s red pile.
o Remove from your red pile and add to your opponent’s black pile.
o Remove from your black pile and add to your opponent’s red pile.
● There should be a log of the game’s events, including the player’s selections and the
computer’s selections.
● There should be a reset button.
Functionality
A player’s turn consists of the following:
1. Roll the dice.
2. Make one of the four choices:
a. Add to your red pile and remove from your opponent’s black pile.
b. Add to your black pile and remove from your opponent’s red pile.
c. Remove from your red pile and add to your opponent’s black pile.
d. Remove from your black pile and add to your opponent’s red pile.
3. Adjust the tokens accordingly (the minimum number of tokens for a player is 0).
4. If either player has no black tokens, the game ends.
For the user, control of the turn is manual, with the user controlling the events by clicking the
buttons.
For the computer, the turn is automatic. The computer will roll the dice and choose one of the
4 options randomly.
For both the player and the computer, you must log every action and display it on screen. The
user should be able to scroll through the log and see all of the actions of the game.
If the game ends (either player has run out of black tokens), the player with the most red
tokens is the winner.
The user may click the reset button at any time. Clear the log and reset each player’s tokens to
12.
Enhancements
● Computer AI
○ Instead of choosing randomly, there is a 75% chance that the computer will
employ one of the following strategies:
■ If the computer has a lead and can maintain it, it will attempt to end the
game by removing black tokens from the smallest black token pile.
● If it can’t maintain the lead, then it will shift red tokens in an
effort to widen its lead.
■ If the computer is behind, it will add black tokens to the smallest pile
regardless of red.
Necessary Programming Skills
● Comprehension of the specifications sheet.
● Planning
o Figure out the information you need to keep track of.
▪ This information will become your global variables.
o Plan out the individual tasks your program must perform.
▪ Think through the steps for each task.
▪ Think through the information your task needs (where does it come
from?).
▪ These will become your functions.
o Plan out the user interface.
▪ You can start with the barest interface, but you should have an idea what
you want the final product to look like.
● Managing your variables
o What’s global, local, and passed through as parameters (hint - this program can
use all three)?
o Do you have a complete back end design (variables and functions that work the
program)?
o Does your back end inform your display?
● Assigning functions as tasks
o Does your program sort out the different tasks into their own functions?
● Sequencing
o Does your program sequence from the user interaction into the necessary
functions?
o Is there an efficiency to your code that flows from the design document?
● An intuitive user experience
o Is your display appropriate to the program (what’s viewable and what scrolling
has to be done)?
o Is your display adaptable to other resolutions?
o Is the interface intuitive?
