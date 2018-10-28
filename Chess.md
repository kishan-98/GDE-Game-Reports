# Game Design and Engineering

## Game Reports: Kishan Sangani: 201501053
### Team Member 2: Sriya Deepika : 20161186

## Chess

### Rule Change:

We introduced a new rule for called _Inverted Jump_.

- Except pawns and king, every other piece can jump over at most one other piece, either of player or their opponent.
- Other rules of game apply as it is.

### Type of rule change:

The new rule is **operational** rule.

### Reason for this change of rule

- The knight was the only piece that could jump over other piece in the board.
- We wanted to give this power even to other important pieces like rook, bishop and queen to enhance their power.

### Game Play
- This change in rule make the game more interesting as there are multiple ways of giving check despite having blocking pieces surrounding the king.
- It makes capture more easier in the game.

### Player Behavior
- Player will now have more attention towards the pawns, of their as well as their opponent as they may be crucial _Wall_ to the _Inverted Jump_ rule change.
- Not only this is advantageous, but a player can lose their own piece if they are not careful.

### Duration of game
- The duration of game remained same but the number of steps were reduced.
- The reason for the reduction in number of steps is that capture and check(probably checkmate) is easier, while the duration of the game remains same because there are multiple capture scenerious possible with a single layer of blockage of pieces, thus it takes more time to evaluate position after one move.

### Game Output
- The game output remains unaffected, however multiple new moves are possible.

### Mathematical Solutions
- Chess is only [partially solved](https://en.wikipedia.org/wiki/Solving_chess), but is [solvable game](https://chess.stackexchange.com/questions/13522/is-chess-a-solved-game).
- The number of moves with the given rule change increases significantly thus it becomes expensive computationally. The states of the game are increased because of introdution of the new rule.
