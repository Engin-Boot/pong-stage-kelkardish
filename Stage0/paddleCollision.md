# paddlCollision

## Feature

This module checks for the collision of the ball and any of the two paddles.

## Acceptance Criteria

### Scenario: Ball collides with a paddle

  Given the game session is running.

  When updateClock module sends wake signal and the ball hits a paddle.

  Then ball inverts in 'X' direction from the point of contact on the paddle
  and its speed increases by 10 percent.
