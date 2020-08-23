# Start-Game-Round

## Feature

Start new game or start game from same position and
score after penalty point

## Acceptance Criteria

### Scenario: Start new game

  Given Player selects color of background and ball and
player is at start new game

  When player selects start new game button

  Then game starts from beginning

### Scenario: Start game from same position and score

  Given Player is playing game

  When Slider miss ball and player scores penalty point
and penalty point is not equal to three

  Then Update score and penalty point of player and
start game from same position and score
