# Tennis Kata (Java TDD version)

This exercice aims at practising TDD in the Java laguage, by implementing a tennis game scoring system.

## Instructions

The goal is to implement a Tennis game scoring system, using TDD.

Each iteration must be clearly identified with its own separate commits for Red/Green/Refactor.

## Tennis game scoring

*(The following is adapted from [Wikipedia](https://en.wikipedia.org/wiki/Tennis_scoring_system))*

A **game** consists of a sequence of points played with the same player serving, and is won by the first player (or players) to have won at least four points by two points or more over their opponent. 

In scoring an individual standard game of tennis, the server's score is always called first and the opponent's score second. Score calling is unique to the sport of tennis in that each point has a corresponding call that is synonymous with that point value.

The corresponding call for points is the following :

- 0	-> "**love**"
- 1	-> "**fifteen**"
- 2 -> "**thirty**"
- 3 -> "**forty**
- 4 -> "**game**"

In tennis, scoring in *tie situations* in which both players have won the same number of points also varies :
- when players are tied by zero, one or two points, the score is described as "**love-all**", "**fifteen-all**" and "**thirty-all**" 
- however, if each player has won three points, the score is described as "**deuce**" rather than "**forty–all**". From this point on, whenever the score is tied, it is described as "deuce" regardless of how many points have been played.

In standard play, scoring beyond a "deuce" score, in which both players have scored three points each, requires that one player must get two points ahead in order to win the game. This type of tennis scoring is known as "advantage scoring" (or "ads"). In this type of scoring, the player who wins the next point after deuce is said to have the advantage. If the player with advantage loses the next point, the score is again deuce, since the score is tied. If the player with the advantage wins the next point, that player has won the game, since the player now leads by two points. When the server is the player with the advantage, the score may be stated by him or her before the next point as "**advantage in.**" When the server's opponent has the advantage, the server may state the score as "**advantage out.**". 

When the server has won the game, the score may be stated by him or her as "**game in.**" When the server's opponent has won the game, the server may state the score as "**game out.**"
