# Game Design and Engineering

## Game Reports: Kishan Sangani: 201501053
### Team Member 2: Sriya Deepika : 20161186

## Checkers

### Rule Change:

We introduced a new rule for called _Parallel Destiny_.

- The destination of each player is not the opponent's cell but the adjacent cell of their opponent(either both left or both right).
- Other rules of game apply as it is.

### Type of rule change:

The new rule is **foundational** rule.

### Reason for this change of rule

- Capture over opponents' pieces makes it easier to move player's piece to other end.
- However, it may turn out to be more advantageous to opponent's piece if player is not careful.
- In order to make each player more dependent on their own rather than their opponent, this rule was introduced.

### Game Play
- Due to this simple rule change, the player can now make their own bridge to their own destination.
- This simple rule change makes the game more asymmetric than the original game.
- The game becomes more interesting, as if both the player know the exact optimal solution of the game, it would be highly advantageous for the player with first move.

### Player Behavior
- If both the player know the exact optimal solution of the game, the player with the second chance has to go at lengths to interfere with the bridges of opponent.
- The player with first move will try to avoid the opponent by making bridges on the far end of their side of destination.
- The strategy of player may now also be influenced by the behavior of the opponent.

### Duration of game
- The duration of game is considerably reduced when played with new rule.
- The reason if both the player know the exact optimal solution of the game, the game could end in steps as less as 29.

### Game Output
- The player with first move has considerably high advantage.
- If both the player are familiar with optimal solution of game, and they know each other well, the game result will probably end in first person winning the game.

### Mathematical Solutions
- As presented in the research article "THE SHORTEST GAME OF CHINESE CHECKERS AND RELATED PROBLEMS
" by George I. Bell, the shortest game remains same.
- However the average length is considerably reduced and the game is more asymmetric than the original game.
