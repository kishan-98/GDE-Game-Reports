
# Game Design and Engineering

## Game Reports: Kishan Sangani: 201501053
### Team Member 2: Sriya Deepika : 20161186

## Checkers

### Rule Change:

We introduced a new rule for called _Crossed Destiny_.

- The destination of each player is not the opponent's cell but the opposite cells of their adjacent side of board(either both left or both right).
- Other rules of game apply as it is.

### Type of rule change:

The new rule is **foundational** rule.

### Reason for this change of rule

- Capture over opponents' pieces makes it easier to move player's piece to other end.
- However, it may turn out to be more advantageous to opponent's piece if player is not careful.
- In order to make each player even more dependent on their own opponent, this rule was introduced.

### Game Play
- Due to this simple rule change, the player can now have multiple bridges to their own destination.
- This simple rule change makes the game compact the original game.
- The game becomes more interesting because they have to be more careful now with their bridges.

### Player Behavior
- The game play have turned more emergent and thus player would try to take even more advantage of their opponent.
- The player with first move will try to avoid the opponent by making bridges on the far end of their side of destination.
- The strategy of player may now also be influenced by the behavior of the opponent.

### Duration of game
- The duration of game is reduced when played with new rule.
- The reason is because the destination is now more closer to the player, they will complete in less number of steps.

### Game Output
- Unlike _Parallel Destiny_, the game remains symmetric.
- The output of the game remain unchanged, but the steps in which the ouptut is achieved is reduced.

### Mathematical Solutions
- As presented in the research article "THE SHORTEST GAME OF CHINESE CHECKERS AND RELATED PROBLEMS
" by George I. Bell, the shortest game remains same.
- However the average length is considerably reduced and the game is similar to the original game.
