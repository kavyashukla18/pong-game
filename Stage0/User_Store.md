# store

## Feature

    buy-background():  append the item bought by player and reduce coin use 
    check-sufficiant-budget() and reduce-coin() update get-background()
    buy-player():  append the item bought by player and reduce coin 
    check-sufficiant-budget() and   reduce-coin() update get_player()
    buy-ball():  append the item bought by player and reduce coin 
    check-sufficiant-budget() and reduce-coin() update get-ball()
    get-background(): return current background
    get-player(): return current player
    get-ball(): return current ball

## Scenario: Buy new background

    Given: game is runing and connected to server
    When: player wants to buy new background
    When: check sufficiant budget 
    If Yes: reduce-coin and append background to user account background list
    Then: buy new back ground
    Else: show error

## Scenario: Buy new player

    Given: game is runing and connected to server
    When: player wants to buy new player
    When: check sufficiant budget 
    If Yes: reduce-coin and append player to user account player list
    Then: buy new player
    Else: show error

## Scenario: Buy new ball

    Given: game is runing and connected to server
    When: player wants to buy new ball
    When: check sufficiant budget
    If Yes: reduce-coin and append player to user account ball list
    Then: buy new ball
    Else: show error

## Scenario: Send background to re-draw the back ground

    Given: game is runing and connected to server
    When: player want to change background
    Then: return back ground from the back ground list

## Scenario: Send player to re-draw the player

    Given: game is runing and connected to server
    When: player want to change player
    Then: return player from the player list

## Scenario: Send ball to re-draw the ball

    Given: game is runing and connected to server
    When: player want to change ball
    Then: return ball from the ball list
