# Interaction Sequences

## start up Sequence

    user-account will run
    user get option to three option
    play, store, user profile

## Scenario: one

    player choose play
    then class player type will invoke
    then invoke class draw
    the invoke class move and timer together
    then invoke class speedr
    then score or penalty will get invoke
    when class timer stop end the game
    class invoke score to show the score
    if user choose user profile

## Scenario: two

    user will have option as class item
    user can change background player and ball

## Scenario: three

    user choose store option
    the invoke store class
    here user can buy new background, player and ball

## Movement Initiation

    1: set_player_choice()
    2: choose_player()
    3: level_choose()
    4: timer()
    5: Compute_speed()
    6: draw_choosen_background()
    7: draw_ball()
    8: draw_wall()
    9: divide_screen()
    10: draw_payer()
    11: move_player()
    12: move_two_player() and start_timer()
    13: mover_ball()
    14: ball_miss() and ball_touch_wall()
    15: get_wall_coordinate() and player_hit()
    16: score_computation()
    17: end_game()
    18: get_score()
    19: total_coin()

## One score

    when user select the player
    invoke draw
    invoke timer
    invoke speed
    game started
    invoke move
    if player hit ball get score
    if player miss ball opponent will get score
    if ball touch the wall get half of hit score
