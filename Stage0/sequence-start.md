# Interaction Sequences

## Start up Sequence

The sequence is as follows : launch Pong game Application-->
PongGame_Menu -->Select-Player-and-enter-name -->
Select-Background-and-Ball-color -->Start-Game-Round -->
Collision-Checker -->Score-count-increment -->Declare-Winner
-->Exit_game

## Movement Initiation
If penalty point reaches to three then compare score of both
players. Declare player with highest score as winner.
After winner declaration player again reaches Menu tab,
either player can start new game or Exit game.

## One score
If collision occurs then Collision-Checker module calls
Score-count-increment module to update score and penalty
points of players.
