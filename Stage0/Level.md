# Level

## Feature

    level-count(): keep the record of level cleared by player
    level-choose(): which level choosen by player
    Level-Activate(): after clearing one level next level get updated
  
## Scenario: Keep the record of level cleared by player

    Given: game is runing and connected to server
    When: player clear the level then store on level player id map
    Then: player can re access cleared level again

## Scenario: Choose level

    Given: game is runing and connected to server
    When: player want to continue or play already cleared level
    Then: player can play any activate level

## Scenario: Activate new level

    Given: game is runing and connected to server
    When: player cleared the current level
    Then: new level get added to the player level list
