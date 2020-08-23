# ball

## Feature

This module represents the game consisting of
one ball, two paddles for two players and their respective scores
and this module declares the winner between the two players

## Acceptance Criteria

### Scenario: to declare winner

  Given pong game is working and threshold value

  When ball collides with the wall
  and ball miss counter of one player exceeds the threshold value

  Then declare one player as the winner which have less ball miss counter
