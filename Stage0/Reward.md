# reward coin

## Feature

    Daily-reward-coin(): set daily reward based on increment-daily-reward-coin()
    increment-daily-reward-coin(): increment based on time span(for how long a
     player is playing the game)
    level-clearnce-coin(): for clearing every level based on score in that level
    (eg multiply score by coin for that level)
    total-coin(): sum level-clearnce-coin() and Daily-reward-coin()
    reduce-coin(): when item bought reduce coin from the total
    check-Sufficient-budget(): if player have enough coin to buy
  
## Scenario: Set daily reward

    Given: game is runing and connected to server
    When: Set the daily reward once player click on that
    the get daily reward will get deactivated till tomorrow
    Then: player will get daily coin as reward

## Scenario: Increase daily reward

    Given: game is runing and connected to server
    When: The increament on daily reward after a certain time span
    Then: Player will get increament int daily reward

## Scenario: Total Coin or reward

    Given: game is runing and connected to server
    When: Player get any reward or coin sum the coin to the current
    Then: player will see "Total coin" as result

## Scenario: Bought item from store

    Given: game is runing and connected to server
    When:  Player buy Item from store reduce coin from current
    Then:  player will see "Total coin" as result after reduction

## Scenario: check the Sufficient budget

    Given: game is runing and connected to server
    When:  Player want to buy an item the check player have
    Sufficient amount or not
    If yes: player see "item added to player account" as result
    Else:
    Then:  player will see "Error" as result
