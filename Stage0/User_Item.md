# user Item

## Feature

    choose-backgroung(): player can buy or use previous one use get-background()
    choose-player(): player can buy or use previous one use get-player()
    choose-ball(): player can buy or use previous one use get-ball()
    bg-id: background ID

## Scenario: change background

    Given: game is runing and connected to server
    When: player want to change the back ground
    Then: get-background() return that background from background list

## Scenario: change player

    Given: game is runing and connected to server
    When: player want to change the player
    Then: get-player() return that player from player list

## Scenario: change ball

    Given: game is runing and connected to server
    When: player want to change the ball
    Then: get-ball() return that ball from ball list
