# Interaction Sequences

## Startup Sequence

```mermaid
sequenceDiagram
Player->>+mainMenu:launches game
mainMenu-->>-Player:start game or exit
Player->>mainMenu:start game
mainMenu->>+gameEngine:"start game"
gameEngine-->>-Player:"begin"
```

## Movement Initiation

```mermaid
sequenceDiagram
Player->>gameEngine:"begin"
gameEngine-->>Player:ball starts from center at random direction
Player->>movement:moves paddle to hit ball
movement-->>gameEngine:ball hits paddle
gameEngine-->>Player:increase ball speed
```
## One score
```mermaid
sequenceDiagram
gameEngine-->>keepScore:ball hits left or right border
keepScore-->>keepScore:increase score by 1
```
