# mainMenu

## Feature

When the game starts, the player will encounter the main menu where they can
choose to start a game or exit the game.

## Acceptance Criteria

### Scenario: Player launches the game

  Given the player has a device that can play the pong game
  
  When the player launches the game

  Then the game launches with a default display resolution and player can see
  the main menu with the items "start game" and "exit".

### Scenario: Player clicks on "start game"

  Given the player has a device that can play the pong game
  and the game has launched to the main menu.

  When the player clicks "start game"

  Then the game begins with score set to zero and a prompt on the screen to
  "begin".

### Scenario: -describe-a-scenario-of-this-module

  Given the player has a device that can play the pong game and the player
  clicks "start game:

  When the player hits any preassigned key to "begin"

  Then the ball starts moving in a random direction starting from the centre
  of the game screen

### Scenario: Player clicks on "exit"

  Given the player has a device that can play the pong game
  and the game has launched to the main menu.

  When the player clicks on "exit"

  Then the game window closes.
