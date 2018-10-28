
# Game Design and Engineering

## Game Reports: Kishan Sangani: 201501053
### Team Member 2: Sriya Deepika : 20161186

## Ludo

### Rule Change:

We introduced a new rule for called _Max Siege_.

- By placing one piece at any place on board, the direction in which maximum capture occurs is only considered.
- If there are multiple direction in which maximum capture is possible, then player can chose any one direction.
- Other rules of game apply as it is.

### Type of rule change:

The new rule is **operational** rule.

### Reason for this change of rule

- Othello is a heavy game to process, with a little initial advantage to the first player. In order to slow game a bit, this rule was introduced.
- It would result in slow but firm state capture of the player on board.

### Game Play
- The game play reduces in terms of number of captures of player.

### Player Behavior
- Player would now have to think more in terms of firm stability on board rather than explosive capture.

### Duration of game
- The number of steps to finish the game increased due to its slow game play.

### Game Output
- Game output would alter as the number of captures by a player is slow.

### Mathematical Solutions
- Othello is purely strategy based game. Corner is of highest importance, edges comes next and then the rest of the board.
- Mobility is defined as the amount of power with which you can drive the game. More specifically to the game of Othello, it's better to maximize the empty squares touching the opponents pieces. With _Max Siege_ rule, the effect of mobility is neutralized as there is only one direction in which capture could occur.
- The rule of unidirectional _Max Siege_ leads to greedy dynamic heuristic. Player has to pick the move which should not decrease their piece more that what can be captured from opponent.
- Mathematically othello is still [an unsolved game](https://en.wikipedia.org/wiki/Reversi#Computer_opponents_and_research). There are atmost 10<sup>28</sup> legal positions and has game tree complexity of order 10<sup>58</sup>. With the inclusion of this rule, the legal positions and game tree complexity remain unchanged but the output of the game would change.

