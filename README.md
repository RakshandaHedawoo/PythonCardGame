# PythonCardGame
Simulating a card game to incorporate pre-built Python code packages to manipulate, manage, and process data. Additionally, to develop computer programs using sequence, selection, and repetition control structures to automate data analysis.
**CARD GAME**
_A friend of yours has come to you to monetize a new, two-player card game they want to sell digitally. The game is based on a portion of a 52-card deck.
The game will only consider the cards with a numerical value between 2 and 10, boxed in red (a total of 36 cards). From this point forward, any reference to deck will mean this 36-card subset of the full deck._

_The goal of the game is for each player to get rid of all their cards. The winner is the player who has the lowest score after one player has run out of cards during a round, or after 50 rounds, whichever comes first. Each card is worth the number of points listed on the card. For example, the 6 of hearts is worth 6 points. The card suit is not important and does not need to factor into the game._

**Example – Round 1:**
Player 1 shows a 7 of hearts and a 4 of clubs, totaling 11.
Player 2 shows a 3 of clubs and 5 of spades, totaling 8.
Player 2 wins the round and Player 1 must add all four cards to their card set.

**Example – Round 2:**
Player 1 shows a 3 of diamonds and 6 of diamonds, totaling 9.
Player 2 shows a 4 of spades and a 5 of clubs, totaling 9.
Tie! Next cards are pulled.

Player 1 shows an 8 of hearts and a 2 of spades, totaling 10.
Player 2 shows a 10 of clubs and a 7 of diamonds, totaling 17.
Player 1 wins the round and Player 2 must add all eight cards to their card set.

_** Note: If a tie occurred after the second set of cards was pulled, a third set of cards would need to be pulled and so forth until the tie is broken, or one of the players runs out of cards._

The game will end after one player runs out of cards such that they cannot complete a round, or 50 rounds have been played, whichever comes first. When one player cannot complete a round, all cards pulled for the round are returned to their original player. Then, whichever player has the lowest total value (points) in their card set wins the game.
