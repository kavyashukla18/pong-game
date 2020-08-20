# score

## Feature

    score-computation(): compute score based on ball_miss() and ball_touch_wall()
    get-score(): return total score

## Scenario: calculate the score

    Given: game is runing and connected to server
    When:  Player score the multipled by the coin for the level
    With:  total number of the ball-hit plus reduce by total penalty 
    Then:  total score get calculated

## Scenario: Show Score

    Given: game is runing and connected to server
    When: player go to player profile
    Then: show player total score
