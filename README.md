# guess-the-number
User vs CPU. Guess the opponent number.

*Just for coding practice*

## Gameplay

**User turn:**
The user and the cpu choose a number.
The difference between the numbers is the user score

**CPU turn**
The user and the cpu choose a number.
The difference between the numbers is the cpu score

**Winner**
The winner is the player whose guess was closer to the opponent number (the score is given by the difference between the two numbers. Lowest score = winner)


## Input checks
- Only numbers between 1 and 100 accepted
- To continue or stop the game, uppercase and lowercase of **y** and **n** are accepted

### Updates May 5t, 2022
- changed the game mechanic: scores are calculated for each game and the final winner is whoever wins more games
- added a welcome and instructions message
- added a function to declare the winner of all the games played
- got and found a solution for a *race condition* 
- fixed variable names
- removed useless variables
