This project develops a simulator and multiple strategies for the dice game Hog. Throughout this project, I use control statements and higher-order functions.

The Rules of Hog:

In Hog, two players alternate turns trying to be the first to end a turn with at least 100 total points. On each turn, the current player chooses some number of dice to roll, up to 10. That player's score for the turn is the sum of the dice outcomes. However, a player who rolls too many dice risks:

Pig Out: If any of the dice outcomes is a 1, the current player's score for the turn is 1.

Free Bacon: A player who chooses to roll zero dice scores points equal to ten minus the value of the opponent score's ones digit, summed with the value of the opponent's score's tens digit.

Feral Hogs: If the number of dice you roll is exactly 2 away (absolute difference) from the number of points you scored on the previous turn, you get 3 extra points for the turn. Treat the turn before the first turn as scoring 0 points. Do not take into account any previous feral hog bonuses or swine swap (next rule) when calculating the number of points scored the previous turn.

Swine Swap: After points for the turn are added to the current player's score, if the absolute value of the difference between the current player score's ones digit and the opponent score's ones digit is equal to the value of the opponent score's tens digit, the scores should be swapped. A swap may occur at the end of a turn in which a player reaches the goal score, leading to the opponent winning.
