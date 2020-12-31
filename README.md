# Visualizing-and-Predicting-NFL-Scores-Machine-Learning-In-Python
In addition to analyzing and visualizing NFL scores, I used Logistic and Multiple Linear Regression to predict the outcomes of NFL games using Python and JupyterNotebooks.

- The data used here comes from the NFL scores dataset from kaggle.com (https://www.kaggle.com/tobycrabtree/nfl-scores-and-betting-data?select=spreadspoke.R)

- In addition to the original data, I 'engineered' some additional columns such as current and away home records, as well as points scored per game as well as points scored against per game for both home and away teams

- The training dataset for the algorithms I used includes games from the 2015-2018 seasons. And the testing dataset included games from the 2019 regular season.

- I used logistic regression in order to predict the outcomes of the game (which team wins/loses)

- I used multiple variable linear regression to predict actual scores and spreads. These are less accurate than the game predictions but I was able to attain 66% accuracy when predicting game outcomes with multiple linear regression


Visualizations:

- First, I created a simple bar graph to show the winning percentages of home teams, home team underdogs, and home team favorites in games since 2000. This shows that there may be evidence behind the idea of 'home field advantage'.

- The second visualization was a heatmap displaying the frequency of different final scores from NFL games since the 2000 season. The more frequent the score occurs, the brighter and warmer the color. This gives an idea of the distribution of scores and the likelihood of their occurence. 

- The next is a set of line graphs, one for each team showing the team's records (winning percentage) as the season progresses. From this we can tell which teams trend up or downwards at the end of the season, this may indicate their performance in the playoffs or in the next season.

- The box and whisker plots show the distributions of the predicted spreads for games and the actual score differences. This shows how unpredictable games can be and how inaccurate spread predictions can be.

- The last visualization was a set of two animated bar graph that changes with each week of the 2019 season. It features teams from the NFC East division and shows their points scored per game as well as points scored against per game throughout the season. These statistics are generally a good indication of performance and correlate to the records of the teams for the 2019 season.

Libraries:

- I used matplotlib for the graphing and matplotlib.animation for the animated bar graphs

- HTML from IPython.display was used in order to display a video of the animated graphs in JupyterNotebooks

- Pandas was used for reading the csv file as well as modifying and querying the dataset

- Numpy was used for performing various operations on arrays for the regression algorithms


Future goals:

- In the future, I would like to scrape for more specific data regarding team performances as well as other statistical NFL trends. I hope to attain a greate accuracy at predicting the spread of games as well as the final outcome. I think there are several other features that could be found or created here. In addition, I believe there may be other machine learning algorithms that may perform well on this dataset.
