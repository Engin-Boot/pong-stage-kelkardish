# collisions

## Feature

This module deals with collisions of the ball with paddle and boundaries.
The assumption here is that player1 plays on the left and player2 on the right.

## Acceptance Criteria

### Scenario: Ball collides with paddle

  Given the game session is running.

  When the ball hits the paddle.

  Then ball reflects from the point of contact on the paddle and
  its speed increases by 10 percent.

### Scenario: Ball collides with top and bottom boundary wall

  Given the game session is running.

  When the ball hits the top or the bottom boundary.

  Then the ball reflects from the point of contact on the top or bottom wall.
  
### Scenario: Ball collides with left boundary wall

  Given the game session is running.

  When the ball collides with left boundary wall.

  Then player2 gets a point and new round starts with ball going in a random
  direction from the middle of the game screen.

### Scenario: Ball collides with right boundary wall

  Given the game session is running

  When the ball collides with right boundary wall.

  Then player2 gets a point and new round starts with ball going in a random
  direction from the middle of the game screen.
