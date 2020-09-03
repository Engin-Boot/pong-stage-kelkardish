# gameSession

## Feature

All features of an active game session goes here.

Features like starting the game, pausing, restarting and exiting a game session

## Acceptance Criteria

### Scenario: Beginning new game

  Given the player has a device that can play the pong game and the player
  clicks "start game:

  When the player hits any preassigned key to "begin"

  Then this module triggers ballMovement module to start moving the ball.

### Scenario: New round begins

  Given the player is in active game session.

  When either player scores a point

  Then ballMovement module is triggerd.
