# updateClock

## Feature

This module sends an update signal to all the other modules.

## Acceptance Criteria

### Scenario: Update collision detection and ball movement

  Given a player has launched the game and plays.

  When every (1/60)th of a second passes.

  Then tell all other modules to wake up.
