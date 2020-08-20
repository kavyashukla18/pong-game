# draw

## Feature

    draw-payer(): use choose-player() to draw player 
    draw-ball(): use choose-ball() to draw ball
    draw-wall(): sets the wall coordinate and draw it
    divide-screen(): divide screen in 2 equal part
    draw-choosen-background(): use choose-backgroung() to draw
    get-wall-coordinate(): return the wall coordinate
    player-hit(): returns does player hits the ball or not

## Scenario: Draw Player

    Given: game is runing and connected to server
    When: user move the Player draw-player will draw player
    at that place 
    Then: user will see player where he want to

## Scenario: Draw ball

    Given: game is runing and connected to server
    When: Player hit the ball the draw ball will draw the ball
    according to move-ball algorithm in a perticular speed
    Then: user will see ball moving

## Scenario: Draw background chosen by user

    Given: game is runing and connected to server
    When: player changed the background before playing the game
    re draw chose background
    Then: user will see new background
