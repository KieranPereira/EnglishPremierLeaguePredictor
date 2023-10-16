# EnglishPremierLeaguePredictor
This notebook was used to predict the matches of the English Premier League (EPL) for matchweek 20. The data was provided in a .csv file from the 2000/01 to 2022/23 seasons [1]. Additional data were added as extra features from external sources [2,3]. These included statistics like home and away possession %, home and away win rate % and home and away rating. Other features were engineered through the use of specific formulae for the home and away attacking and defencive strength.

The next section discusses about data imported into a pandas data frame and the concept of differential was introduced. Next, there was data transformation and exploration where the rolling averages for the given fetaures were found for different number of games.

In the methodology section, different models were implemented from scikit learn and then they were trained using the grid search algorithm to give the best accuracy.

Finally, the results were shown for the future matches using the best model and the relative feature importance was shown.

[1] England Football Results Betting Odds | Premiership Results & Betting Odds [Internet]. Football-data.co.uk. 2022 [cited 2023 Jan 3]. Available from: https://www.football-data.co.uk/englandm.php

[2] Premier League Team Statistics | WhoScored.com [Internet]. Whoscored.com. 2023 [cited 2023 Jan 3]. Available from: https://www.whoscored.com/Regions/252/Tournaments/2/Seasons/1849/Stages/3115/TeamStatistics/England-Premier-League-2009-2010

[3] Simulating a Football Season [Internet]. IB Maths Resources from Intermathematics. IB Maths Resources from Intermathematics; 2019 [cited 2023 Jan 3]. Available from: https://ibmathsresources.com/simulating-a-football-season/

The Project was created as part of a group coursework for a machine learning and neural computation module
