# move

## Feature

    move-player() : use choose-player() to call move-two-player() or move-system-player()
    move-two-player() : user get-wall-coordinate() game between two human
    move-system-player(): use system algo to move and get-wall-coordinate()
    mover-ball(): system algo to move ball
  
## Scenario: player plays with system

    Given: game is runing and connected to server
    When: player select system as opponent and system knows
    Algorithm
    Then: player will play with system

## Scenario: what player type is chosen

    Given: game is runing and connected to server
    When: player wan to play with system or another player depend on
    class choose player and get the coordinate of play window
    Then: system will know player choice

## Scenario: player want to play with another player

    Given: game is runing and connected to server
    When: player plays with another player use class draw to get the 
    coordinate of play window and keep the players within
    Then: player exist or not

## Scenario: ball movement

    Given: game is runing and connected to server
    When: system will direct the ball to the angel according to
    which part it touch the player as well as other aspect
    Then: the ball movement will be random
