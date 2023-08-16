# Mips-Blackjack
A blackjack game implemented in MIPS assembly language.The only software I used to create and compile my code was MARS.

User input is pretty simple for this program. The first input the user has to input a number
between 1 and 3 to choose how many players will be in the game. Secondly, the player has to
input their bet using numbers between 1 and their total money. Thirdly, during the game the
player has the choice of inputting the numbers 1 or 2. The number 1 is to let the program know
to generate a new random card while entering the number 2 will make the program skip to the
next player. For each input I set up a user input error so that if the user enters something outside
the range they're supposed to, the game will show an input error message and ask for the input
again

The game is set up in rounds, so
it is all a big loop with different outcomes and possibilities. To begin, the game shows each
player’s total money so they know how much they can bet for that round. Before the game starts,
it asks each player how much they would like to bet for that round. I had to make some
adjustments to the code so that it would skip asking players that were already out of money.
Once players who still had money made their bets, the turn would begin in order from player 1 to
3. Each player receives two random cards, then depending on what they get, the player can enter
the number 1 to receive a new card or press 2 to hold and move on to the next player. Once all of
the players have gone through their turn, I coded sort of an algorithm for the computer (dealer) to
know whether to hit or hold. Lastly, once the players had gotten their turn as well as the dealer,
the game would then compare cards and determine the winner, losers, or those who ended up in a
draw against the dealer.

