# Declare-Winner

## Feature

Compare score of two players and declare winner with highest score

## Acceptance Criteria

### Scenario: Winner declaration to Player 1

  Given Player 1 is playing game versus computer or other player
and penalty point equal to three

  When Score of Player 1 is greater than Player 2 or computer

  Then Declare Player 1 as winner

### Scenario: Winner declaration to Player 2 or computer

  Given Player 1 is playing game versus computer or other player
and penalty point equal to three

  When Score of Player 2 or computer is greater than Player 1

  Then Declare Player 2 or computer as winner

### Scenario: Tie or equal score

  Given Player 1 is playing game versus computer or other player
and penalty point equal to three

  When Score of Player 1 is same as Player 2 or computer

  Then equal score and Tie situation
