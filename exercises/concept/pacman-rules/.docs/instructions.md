# Instructions

In this exercise, you need to translate some rules from the classic game Pac-Man into Unison functions.

You have four rules to translate, all related to the game states.

> Don't worry about how the arguments are derived, just focus on combining the arguments to return the intended result.

## 1. Define if Pac-Man eats a ghost

Define the `pacmanRules.eatGhost` function that takes two arguments (_if Pac-Man has a power pellet active_ and _if Pac-Man is touching a ghost_) and returns a boolean value if Pac-Man is able to eat the ghost. The function should return true only if Pac-Man has a power pellet active and is touching a ghost.

```unison
pacmanRules.eatGhost: Boolean -> Boolean -> Boolean
pacmanRules.eatGhost powerPelletActive touchingGhost =
  todo "implement eatGhost"
```

## 2. Define if Pac-Man scores

Define the `pacmanRules.score` function that takes two arguments (_if Pac-Man is touching a power pellet_ and _if Pac-Man is touching a dot_) and returns a boolean value if Pac-Man scored. The function should return true if Pac-Man is touching a power pellet or a dot.

```haskell
pacmanRules.score: Boolean -> Boolean -> Boolean
pacmanRules.score powerPelletActive touchingDot =
  todo "implement score"
```

## 3. Define if Pac-Man loses

Define the `pacmanRules.lose` function that takes two arguments (_if Pac-Man has a power pellet active_ and _if Pac-Man is touching a ghost_) and returns a boolean value if Pac-Man loses. The function should return true if Pac-Man is touching a ghost and does not have a power pellet active.

```unison
pacmanRules.lose : Boolean -> Boolean -> Boolean
pacmanRules.lose powerPelletActive touchingGhost =
  todo "implement lose"
```

## 4. Define if Pac-Man wins

Define the `pacmanRules.win` function that takes three arguments (_if Pac-Man has eaten all of the dots_, _if Pac-Man has a power pellet active_, and _if Pac-Man is touching a ghost_) and returns a boolean value if Pac-Man wins. The function should return true if Pac-Man has eaten all of the dots and has not lost based on the arguments defined in part 3.

```unison
pacmanRules.win : Boolean -> Boolean -> Boolean -> Boolean
pacmanRules.win eatenAll powerPelletActive touchingGhost
  todo "implement Rules.win"
```
