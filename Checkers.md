# Game Design and Engineering

## Game Reports: Kishan Sangani: 201501053
### Team Member 2: Sriya Deepika : 20161186

## Checkers

### Rule Change:

We introduced a new rule for the king and the piece would be called _Mighty King_.

- Once a _Men_ becomes _Mighty King_, the piece can move in all **8** direction.
- Other rules of game apply as it is on the _Mighty King_ piece.

### Type of rule change:

The new rule is **operational** rule.

### Reason for this change of rule

- Capture over opponents' pieces is possible if player's piece can jump over them.
- If the opponents' pieces are diagonally consecutive, it is not possible to capture them.
- However, if _Mighty King_ piece comes to the adjacent cells(not diagonal) to one of opponents' pieces, then it can capture multiple pieces.

### Game Play
- The game play now becomes interesting, as the king has more ways to capture the opponents' pieces.
- King is considered an important object of the game, is now laid with more powers and thus it becomes crucial if any player becomes successful in converting _Men_ piece to _Mighty King_ piece.

### Player Behavior
- Player may now focus more on converting their _Men_ pieces to _Mighty King_ piece.
- If one of opponents' pieces becomes king, the player than tries to be more careful with their own game play.

### Duration of game
- The duration of game reduced when played with new rule and piece.
- The reason is that now the _Mighty King_ piece can capture the pieces which once would have taken more steps to capture, thus reducing the moves required to play game.

### Game Output
- The player with _Mighty King_ piece has higer advantage than other, thus it could be deciding factor in game.
- With the same moves as in the original game, the _Mighty King_ piece has potential to convert a draw/losing game to winning/draw game.

### Mathematical Solutions
- The intial gameplay remains same until one of the _Man_ piece becomes _Mighty King_.
- As presented in the research article "Checkers Is Solved" by Jonathan Schaeffer et. al, the endgame databases have to be modified as there are more possible moves for the prior _King_ piece.
- The flow of the algorithm remains same but the possible moves for the piece increases, thus it becomes computationally more expensive.
