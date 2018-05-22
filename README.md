

### Description

The agent will use the **alpha-beta search algorithm**
and the **expectimax search algorithm** to select the
next move given the current board state.

There are two main files:
- ConnectFour.py
- Player.py

ConnectFour.py contains the all of the functions of the game.
Player.py contains all of the types of players that can participate in the
game:
- AIPlayer 
- RandomPlayer (Chooses from valid columns with equal probability)
- HumanPlayer (You)


To play the game run the following command:

`python ConnectFour.py arg1 arg2`

Where `arg1` and `arg2` are one of `ai`, `random`, or `human`

For example if you wanted to play against a random player you would run:

`python ConnectFour.py human random`

**Note: A human player has to enter their move into the terminal**

If you wanted your ai to play itself you would run:

`python ConnectFour.py ai ai`

`ConnectFour.py` takes one optional argument `--time` that is an integer. It is
the value used to limit the amount of time in seconds to wait for the AI player
to make a move. The default value is 5 seconds.


![game](game.png)

The top text displays the player who's move it is.

The well drawn circles in the middle are the places places on the gameboard

The next move button does exactly what your expect, it moves the game forward
by one move.

When the game is over the top text will change to the name of the winning player
and 'wins!'

Shown below is an example where I managed to get the best of a Random player:

![game-over](game-over.png)



### Relevant Resources
**Alpha-Beta**

![alpha-beta-search](alpha-beta-search.png)

**Expectimax**

![expectimax](expectimax.png)
