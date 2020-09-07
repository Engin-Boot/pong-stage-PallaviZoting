# Start-Game-Round

## Feature

Start new game round or start same game
with same score after user gets penalty point

## Acceptance Criteria

### Scenario: Start new game

Given Player selects color of background
and ball and player is at start new game

When player selects start new game button

Then game starts from beginning with fixed
ball and slider position

### Scenario: Start game from new position and same score

Given Player is playing game

When Slider miss ball and player scores penalty point
and penalty point is not equal to three

Then Update score and penalty point of player and start
game from new position of ball and same score as running game
