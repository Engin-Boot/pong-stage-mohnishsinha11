# ball

## Feature

This module represents the ball and ball have following data members
coordinates x and y to represent its position w.r.t origin at top and left
height and width of ball
methods to check collisions
and to move the ball
and to change direction of ball
and to display ball
and velocity

## Acceptance Criteria

### Scenario: when paddle hits the ball

  Given the paddle moves properly
  and velocity of ball
  and type of collision
  and rest of the pong game is running properly

  When change direction function is called

  Then change coordinates of the ball with respect to type of collision

### Scenario: when ball hits the ceil or floor

  Given the paddle moves properly
  and velocity of ball
  and type of collision
  and rest of the pong game is running properly

  When ball collides with the ceil or floor

  Then call the function to change the direction of the ball
