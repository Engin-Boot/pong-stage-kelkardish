# keepScore

## Feature

This modules maintains the score of both players and decides who wins the game.

## Acceptance Criteria

### Scenario: Either player scores a point

  Given the game session is running

  When boundaryCollision module detects collision on left or right side wall.

  Then increase score of Player2 or Player1 by 1 point respectively.

### Scenario: Decide the winner

  Given the game session is running

  When one of the player scores 10 points

  Then declare that player as winner and prompt the player to either
  restart the game or go to main menu.
