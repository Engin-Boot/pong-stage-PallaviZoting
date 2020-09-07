# Collision-Checker

## Feature

It is used to check position of ball
and collision detection

## Acceptance Criteria

### Scenario: Ball collides with wall of opposite player

Given Game is running and slider of one player hits ball

When slider of other player miss ball and ball hits
the vertical wall of opposite player

Then call “Score-count-increment” module to update score
and penalty points and game starts with new position of ball and slider

### Scenario: Ball collides with slider of opposite player

Given Game is running and slider of one player hits ball

When ball hits the slider of opposite player

Then call “Score-count-increment” module to update score points and
ball goes in opposite direction and game starts with same position of ball and slider
