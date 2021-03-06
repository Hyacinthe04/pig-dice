# Pig Dice
Pig Dice is a game of luck and intrigue where players roll a die until they get a one or choose to stop and bank their total. First player to bank 100 points wins. {january 2019}
By {Hyacinthe Ndayiragije}
# Description
A simple dice game. Each turn, a player repeatedly rolls a die until either a 1 is rolled or the player decides to "stay":

If the player rolls a 1, they score nothing and it becomes the next player's turn.
If the player rolls any other number, it is added to their turn total and the player's turn continues.
If a player chooses to "hold", their turn total is added to their score, and it becomes the next player's turn.
The first player to score 100 or more points wins.
# Specifications

Display a random number between 1 and 6.

Input: "Roll"

Output: 4

Add the number from each roll to a total.

Input: 4, 2, 5

Output: 11

If 1 is rolled, reset total to 0 and end turn.

Input: 4, 2, 5, 1
Output: 0
End turn manually and add "turn total" to bank.

Input: 4, 2, 5, stop
Output: 11 = 11
Switch to another player and keep a separate bank.

Input: player 1 stops at 11

Output: player 2 starts at 0

End game when one player's bank reaches 100.

Input: player 2 bank = 101

Output: Congratulations player 2!

# Setup/Installation Requirements
Source code available at repository

# Known Bugs
Turn total does not display on second roll on easy computer's turn.

# Support and contact details
Contact one of the authors at: hyacinthen04@gmail.com
# published page
https://hyacinthe04.github.io/pig-dice/

# Technologies Used
jquery
Bootstrap
javascript
html/css
# License
This project is licensed under the MIT license.

Copyright (c) 2019 {Hyacinthe Ndayiragije}

