# Start-Game-Round

## Feature

Start new game or start game from same position and
score after penulty point

## Acceptance Criteria

### Scenario: Start new game

  Given Player selects color of background and ball and
player is at start new game

  When player selects start new game button

  Then game starts from beginning

### Scenario: Start game from same position and score

  Given Player is playing game

  When Slider miss ball and player scores penulty point
and penulty point is not equal to three

  Then Update score and penulty point of player and
start game from same position and score
