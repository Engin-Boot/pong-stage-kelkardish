# boundryCollision

## Feature

This module checks for the collision of the ball and any of the four boundry
walls.

## Acceptance Criteria

### Scenario: Ball collides with top and bottom boundary wall

  Given the game session is running.

  When updateClock module sends wake signal and ball hits the top or the
  bottom boundary.

  Then the ball inverts in 'Y' direction from the point of contact on the top
  or bottom wall.

### Scenario: Ball collides with left boundary wall

  Given the game session is running.

  When updateClock module sends wake signal and ball collides with left
  boundary wall.

  Then player2 gets a point and new round starts with ball going in a random
  direction from the middle of the game screen.

### Scenario: Ball collides with right boundary wall

  Given the game session is running

  When updateClock module sends wake signal and ball collides with right
  boundary wall.

  Then player1 gets a point and new round starts with ball going in a random
  direction from the middle of the game screen.
