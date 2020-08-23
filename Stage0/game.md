# ball

## Feature

This module represents the game consisting of
one ball, two paddles for two players and their respective scores
and this module declares the winner between the two players

## Acceptance Criteria

### Scenario: to start the game

  Given start button and two paddles and a ball
  and initially ball is cling to the center of paddle "1"

  When user presses the start button

  Then release the ball from paddle "1" and move the ball

### Scenario: to declare winner

  Given pong game is working and threshold value

  When ball collides with the wall
  and ball miss counter of one player exceeds the threshold value

  Then declare one player as the winner which have less ball miss counter
