# Supervised Learning Capstone: Predicting Wins for League of Legends

In this model, we will be using several different classifiers to predict wins for League of Legends.  Here's the original [link](https://www.kaggle.com/datasnaek/league-of-legends#games.csv) for this dataset.  

The game consists of two teams with 5 players each.  Through a coordinated team effort & skill, each team tries to win by destroying the other team's nexus.  Before the game, each player gets to choose a champion to play.  In addition, they get to choose two summoner spells (order of spells doesn't effect gameplay). And finally, each team gets to ban 5 champions.  Banned champions won't be able to be used by either team.  After these decisions are made, the game starts.

Our goal is to predict the winner of each match using the following: champion choices, ban choices, & summoner spell choices.  Although kill counts & game duration are included in this dataset, we will NOT be using these metrics.  We want to see if we can predict the winner before the game starts.  Because of this, we will not use metrics that accrue after the game starts.  

Our model would be useless if we need to watch an entire match to determine the winner.
