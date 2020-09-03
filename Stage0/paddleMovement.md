# paddleMovement

## Feature

This module focuses on how the paddle moves. The movement keys for now
configured are "up arrow" and "down arrow" for player 1, and
"w" and "s" for player 2.

Note that +Y translates to moving down on the screen and -Y is moving up.

## Acceptance Criteria

### Scenario: when player 1 presses "up arrow" key

  Given a player has launched the game and plays.

  When the player 1 presses "up arrow" key

  Then the paddle moves in -Y direction with constant speed factor.

### Scenario: when player1 presses "down arrow" key

  Given a player has launched the game and plays.

  When the player 1 presses "up arrow" key

  Then the paddle moves in +Y direction with constant speed factor.

### Scenario: when player2 presses "w" key

  Given a player has launched the game and plays.

  When the player 2 presses "w" key

  Then the paddle moves in -Y direction with constant speed factor.

### Scenario: when player2 presses "s" key

  Given a player has launched the game and plays.

  When the player 2 presses "s" key

  Then the paddle moves in +Y direction with constant speed factor.
