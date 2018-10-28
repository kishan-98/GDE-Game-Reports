
# Game Design and Engineering

## Game Reports: Kishan Sangani: 201501053
### Team Member 2: Sriya Deepika : 20161186

## Ludo

### Rule Change:

We introduced a new rule for called _Split the Move_.

- The count throw of the dice can be splitted between at most two pieces.
- Steps moved by one or sum of steps moves by both the pieces must be equal to the count of throw of dice.
- Other rules of game apply as it is.

### Type of rule change:

The new rule is **operational** rule.

### Reason for this change of rule

- Towards the end of the game, the turns of the player are wasted as player might not get the exact move to win. To help with this, the rule was introduces.
- Splitting the dice throw helps, and restriction over the total steps and the number of pieces in distribution restricts the player from exploiting the rule.

### Game Play
- The game play turned out to be interesting as with the _Split the Move_ rule, most utilization of steps of pieces occurs in terms of reaching the home, capturing opponent's piece or using the shortcut.

### Player Behavior
- Player will now more often try to split the dice throw for maximum utility.

### Duration of game
- The number of steps to finish the game increased with the use of this rule as more capture could be done by _Split the Move_ rule.
- If there are no capture throughtout the game, the average number of step would reduce.

### Game Output
- Game output may alter as capturing of opponent's pieces is highly possible.

### Mathematical Solutions
- According to [this](https://pdfs.semanticscholar.org/2b63/277508b6d2909ff75c18c5c098ce64135dca.pdf) research paper make AI Bot with optimal search techniques. The most important aspect of AI Bot in Ludo is that it should be [fun to play with](https://stackoverflow.com/questions/5163806/how-to-make-an-efficient-ludo-game-playing-ai-algorithm).
- With the above change in rule, the algorithms have to search more broadly across the new possible combinations of the split between two pieces. The computation complexity would increase with this change of rule.
- The breadth of the search tree would increase, but the depth of the search tree would decrease as what could be achieved by two dice throw in original game could probably be achieved in one dice throw with new rule.
