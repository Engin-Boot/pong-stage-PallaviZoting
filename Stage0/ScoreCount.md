# Score-count-increment

## Feature

Increment score of player by one and update score count

## Acceptance Criteria

### Scenario: Increment score of player1

  Given Player1 is playing game versus computer or other player

  When Player1 slider hits ball and ball goes in opposite direction

  Then Increment the score of player1 by one and update score count
  
### Scenario: Increment score of Player2 or Computer
  Given Player1 is playing game versus computer or other player
  
  When Computer slider hits ball or other player slider hits ball
and ball goes in opposite direction
  
  Then Increment the score of computer or player2 by one and
update score count
