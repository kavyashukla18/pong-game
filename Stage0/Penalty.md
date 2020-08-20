# penalty

## Feature

    ball_touch_wall(): checks the ball is toching the wall of which player 
    use get-wall-coordinate()
    ball-miss(): if player failed to pass the ball to the other half of the 
    screen user get-wall-coordinate() and player-hit()

## Scenario: Ball touches any of the wall

    Given: game is runing and connected to server
    When: Ball any of the wall charge penalty 
    Then: reduce score

## Scenario: Player miss the ball

    Given: game is runing and connected to server
    When: Player miss the ball use player-hit()
    Then: reduce score
