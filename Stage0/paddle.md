# paddle

## Feature

This module represents the paddle class and it has following data members
members to store the coordinates x and y
which represents position of paddle from top and left,
height and width of paddle
and the ball miss counter for the player using the paddle
and it also consists of method for movement of paddle in verticle direction
and method to display the paddle
and velocity

## Acceptance Criteria

### Scenario: to move paddle upwards with given velocity

  Given display and move method for ball and paddle
  is functioning correctly in pong game
  and velocity of paddle

  When the user presses the up button

  Then move the paddle upwards with given velocity

### Scenario: to move paddle downwards with given velocity

  Given display and move method for ball and paddle
  is functioning correctly in pong game
  and velocity of paddle

  When the user presses the down button

  Then move the paddle downwards with given velocity

### Scenario: when paddle misses the ball update the score

  Given display and move method for ball and paddle
  is functioning correctly in pong game

  When the paddle misses the ball

  Then increment the ball miss counter

### Scenario: when ball hits the paddle change the direction of ball

 Given display and move method for ball and paddle
 is functioning correctly in pong game

 When the paddle hits the ball

 Then call the function to change the direction of the ball
