# Simultaneous move games
In prisoner's dilemma, individual strategic optimizations leads to " lose-lose" situation. no player have incentive to change his strategies.When there is a strictly dominant strategy, a player can safely remove all other strategies, and that make the predict of the result very easy.

As to the strictly dominant strategy is easily to predict, most games do not have strictly dominant strategy.

We change to find the strictly dominated strategies.(For player 1, strategy  x  is **strictly dominated** if choosing x  always leads to a strictly less payoff than choosing another strategy y, independent of player 2's choice)

The characters of strictly dominated strategy:
* A strictly dominated strategy may not be the worst
* We can safely remove a strictly dominated strategy, as it will never be played and it will not affect the game outcome.
* If there are multiple strictly dominated strategies, they can be removed in any order.
* New strictly dominated strategy might emerge during the removing process.

**Nash Equilibrium**
A pair of strategies form a Nash Equilibrium if each player is choosing the best response given the other player's strategy choice.
At a Nash equilibrium, no player can perform a profitable deviation unilaterally.
**Coordination Games**
In coordination Games, players get mutual benefits when they choose the same actions.
Symmetric coordination game: stag hunt.
Asymmetric coordination game: battle of sexes.
**Anti-Coordination Game**
In anti-coordination game, it is beneficial for players to choose different strategies.
**Finite game**
Finite number of players, and each player has finite number of strategies.
**Theorem **
There exists at least one Nash equilibrium for every finite game, and such an equilibrium may involve mixed strategies.

# Sequential move games

**Sequential move games**: Players make decisions at different time and different stages.(a theory of commitments or threats)

**Principle of sequential rationality**: equilibrium strategy should be optimal at every point of the game tree.so we examine each subgame through backwrd induction.

**Subgame perfect Nash equilibrium(SPNE)**
 A strategy profile is a subgame perfect Nash equilibrium if it is a Nash equilibrium of every subgame of the original game.
 SPNE is a contingency plan that spcifies the action at every point of the game tree.

**Credible threat**
One way to creat a credible threat for player moves later is to eliminate some of his options.

**Forward induction**
A player assumes that all previous actions are rational when he makes a decision.

# Continuous game

**Weakly dominant** means that it will lead to a payoff for a bidder no smaller than any other choices,independent of any other bidders choice.

**Centipede game** raise a question, why people not follow subgame perfect Nash equilibrium? One popular answer is that fairness is an important concern.

**Payoff modification**
Each player's payoff is parameterized by two coefficients: Ai and Bi. Ai is the fairness coefficient Ai max(yj-yi,0). Bi is the guilt coefficient Bi max(yi-yj,0).
Player i's payoff is Ui(yi,yj) = yi-Ai max(yj-yi,0) - Bi max(yi-yj,0).
 
