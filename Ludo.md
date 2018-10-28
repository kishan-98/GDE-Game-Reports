
# Game Design and Engineering

## Game Reports: Kishan Sangani: 201501053
### Team Member 2: Sriya Deepika : 20161186

## Checkers

### Rule Change:

We introduced a new rule for called _Quad-directional Word_.

- The word can be interpreted unconvenctional direction like right to left and down to up apart from convenctional direction left to right and up to down.
- The score is calculated independently for each direction.
- Other rules of game apply as it is.

### Type of rule change:

The new rule is **foundational** rule.

### Reason for this change of rule

- Palindromes are words which read same in either direction.
- Although there are very less palindromes, they are not given the proper significance over the other words. This rule gives proper significance to the palindromic words.
- Apart from palindromes, if the word is formed from right to left in the original game, it was not given any reward. This rule even takes care for that scenerio.

### Game Play
- This change in rule make the game more interesting as there are bonus points for the palindromes and the words interpreted in the reverse direction.
- Although the formation of words depends on the alphabetic letter picked by player randomly, still there is probability that player can build the word in unconvenctional direction as well.

### Player Behavior
- Player will now have more attention towards formation of words in the unconvenctional direction as well.
- Not only this is advantageous, but a player can lose score if they don't pay attention toward the words.

### Duration of game
- The duration of game and number of words to complete game/pieces reduces as the words are even considered in unconvenctional direction.

### Game Output
- The game output remains unaffected, however average scores of individual increases due to interpretation of words even in unconvenctional direction.

### Mathematical Solutions
- [Maven](https://en.wikipedia.org/wiki/Maven_(Scrabble)) is and Artificial Intelligent Scrabble player which is dependent on [Suffix Automation](https://en.wikipedia.org/wiki/Suffix_automaton) Algorithm. It created graph with node as letters and unidirectional edges as the link between the letters in words and search for the suffix which could extend the current word with letters in the bag for meaningful word.
- The only change in the algorithm is that the there would be multiple graph(one for each unconvenctional direction) and the processing for each graph would remain same.
- The computations and space complexity of the algorithm would increase, but it would not be that significantly high.

