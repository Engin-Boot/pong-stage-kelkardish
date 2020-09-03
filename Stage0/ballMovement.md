# ballMovement

## Feature

All features of an active game session goes here.

Features like starting the game, pausing, restarting and exiting a game session

## Acceptance Criteria

### Scenario: Beginning new game

  Given the player is in active game session and has pressed key to "begin".

  When the player hits any preassigned key to "begin".

  Then the ball starts from the center of the screen and starts moving in
  random direction.

### Scenario: Ball movement in active game session

  Given the player is in active game session.

  When updateClock sends wake signal

  Then ball position updates on the screen depending on its previous position and
  the current velocity of the ball.

### Scenario: New Round starts

  Given the player is in active game session.

  When new round triggers this module

  Then the ball starts from the center of the screen and starts moving in
  random direction.
