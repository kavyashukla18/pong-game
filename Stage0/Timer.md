# Timer

## Feature

    timer(): set game time base on level_choose()
    end_game(): call timer() to end the game
    start_timer(): reset the timer
  
## Scenario: Set game time base on level choose by player

    Given: game is runing and connected to server
    When: player can choose any level which he cleared 
    Then: timer get set according to the level which stored in
    time level map

## Scenario: start timer

    Given: game is runing and connected to server
    When: player start the game
    Then: timer will started using start-timer()

## Scenario: End timer

    Given: game is runing and connected to server
    When: when start timer is equall to end timer
    Then: The game will end
