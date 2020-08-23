# ball

## Feature

This module represents the game consisting of
one ball, two paddles for two players and their respective scores
and this module declares the winner between the two players

## Acceptance Criteria

### Scenario: to start the game and initialize the enviornment

  Given start button and two paddles and a ball
  and initially ball is stick to the centre of paddle1
  
  When user presses the start button
  
  Then release the ball from paddle1 and move the ball
	
### Scenario: to declare winner

  Given pong game is working and threshold value

  When ball collides with the wall
  and ball miss counter of one player exceeds the threshold value

  Then declare one player as the winner which have less ball miss counter
