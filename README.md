# Using machine learning to predict who will win the 2019 World Series

Our primary data source was https://www.baseball-reference.com. We were able to download CSVs that covered fielding, pitching and hitting statistics by team for the season as well as the outcomes of all games played by each team. We then joined these together into one dataframe to create our model.

We ran several models to see which gave the highest score looking at just the Astros and Nationals, just division winners, all teams and all teams with only selected features. All ranged between .57-.61 in accuracy. We ended up using the model based on all team stats. We then fed the statistics for just the Astros and Nationals and used the predict_proba function in random forest to get the probability of each team winning.

# World-Series-Prediction
