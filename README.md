# Poker

## Menu
![menu](https://github.com/alexxuyaowen/poker/blob/main/demo/menu.png)
- Select a feature and press enter, case insensitive.

## Advice
![advice0](https://github.com/alexxuyaowen/poker/blob/main/demo/advice0.png)
![advice](https://github.com/alexxuyaowen/poker/blob/main/demo/advice.png)
- The main feature of the app, allowing the user to compute their winning chance based on the known conditions.
- Once the winning chance is known, the user is expected to make a rational move by following the advice provided by the program. A rational move is defined as a move that has positive expected mathematical gains. For example, the best possible starting hand in Texas Hold'em is AA, in a table consist of 9 players, the person who holds a pair of Aces has a winning chance of around 35% (as computed by the program), whereas the possible gain is 8 times the bet and the possible lose is the bet. Let x be the amount of bet, then the gain would be 0.35 * 8x - (1-0.35)x = 2.15x, which is quite considerable. However, if the flop is pretty bad, holding a pair of Aces would have a winning chance of less than 8% (as shown in the demo picture), which results in the gain to be 0.08 * 8x - (1-0.08)x = -0.28x. As a general rule of thumb, with n players, one should only consider making a bet with a winning chance highter than 1/n.

## Analysis
![analysis](https://github.com/alexxuyaowen/poker/blob/main/demo/analysis.png)
- Display a list of probabilities regarding how a hand would win during showdown.

## Compete Against
![c](https://github.com/alexxuyaowen/poker/blob/main/demo/c.png)
- Display a list of hands competing against a given hand, sorted by winning rate from highest to lowest. For example, the best hand to play against a pair of Aces is not a pair of Kings or Ace King suited, but 7-8 suited (in fact, Ace-King has a far below-average performance against AA).

## Dual
![dual](https://github.com/alexxuyaowen/poker/blob/main/demo/dual.png)
- 

## Ranking
![ranking](https://github.com/alexxuyaowen/poker/blob/main/demo/ranking.png)
- Given a number of players, display a ranking list of hands, sorted by winning rate from highest to lowest. For example, the top 10 best hands to play in a table consists of 6 players are AA, KK, QQ, JJ, AK_suited, AQ_suited, 10-10, AJ_suited, KQ_suited, AK_off-suit.

## Simulator
![simulator](https://github.com/alexxuyaowen/poker/blob/main/demo/simulator.png)

## Statistics
![stat](https://github.com/alexxuyaowen/poker/blob/main/demo/stat.png)

## Help
![help](https://github.com/alexxuyaowen/poker/blob/main/demo/help.png)

