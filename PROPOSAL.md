# Topic Group H:  League of Legends
## What is the league of legends?
League of Legends is one of the top Multiplayer Online Battle Arena (MOBA). The purpose of gamer is how to win the game in which each game divides into two teams which are red and blue teams. The basic principle to win is that which team reaches the base and destroys the nexus faster than the other will end the game whilst defending their own base. However, there are many factors that a team can win a game ranging from blood, baron, dragon to towers, inhibitors. The players stated that these factors mentioned above contributed the most for the winning team.
## Hypothesis
Based on a Kaggle challenge, there are some related questions such as how to win a game, how to predict the outcome, which factors impact the most in the game. 
https://www.kaggle.com/bobbyscience/league-of-legends-diamond-ranked-games-10-min/kernels

Therefore, there are two raising questions: what factors or features define a team will win a game of League of Legends and how to use a prediction model to identify what teams will win the game.
Notice: Our group will not use the data set in the Kaggle but use other methods to collect the data on the Internet. 
 
## Project Goals:
1. What factors define a team will win a game.
2. Using distinct methods to predict the outcome of a team in the game.
## Dataset
The data sets of League of Legends are collected by using the Riot Game API which is used by developers to build applications or websites and return the data in JSON format. By using the Rest API from the Riot, we can collect massive information such as matching history and details, service status, player’s information etc. Especially, we can collect all the factors that influence the winner, because all this information is based on the results of the professional matches.
A guide of the Riot Game API can be founded in the link:<br>
https://towardsdatascience.com/how-to-use-riot-api-with-python-b93be82dbbd6 <br>
To collect the data by using API, we have a python program to collect the data and extract it from the JSON format and then save it to the csv for further process. The headings of the csv data set have a format as follows:
[ ‘gameid’, ‘url’, ‘date’, ’game’, ’patch’, ’playerid’, ’side’, ’position’, ’player’, ’team’, ‘champion’,..., ‘gamelength’,’result’,’kills’,’deaths’,...]
The detail of column or attributes in the CSV file will explain in the document below:
* LOL_data_column_descriptions.docx
## Visualize Techniques
Based on the Exploratory Data Analysis represented by John Tukey, the greatest value of plotting graphs before analyzing it contributed to the overview of what we can do and view the results and correlation between variables. Our group can apply some techniques for drawing graphs by using matplotlib or seabon data visualization such as distribution plots, categorical plots, regression plots. 
## Analysis Techniques
Some techniques are expected in this project to analyze the clean and formatted data set which are categorized in prediction, evaluation, features collection, and parameter analysis. For the prediction, some methods are K-means clustering, linear regression, logistic regression, k-Nearest Neighbors or decision tree. In addition to the prediction technique, some methods such as Mean Square Error, Mean Absolute Error and R-squared, F-score, AUC are also applied to evaluate the model corresponding techniques. The neural network is also used to enhance the performance of our project. However, our group will consider eliminating or adding techniques when implementing the project. 
In this project, we will use unsupervised learning especially classification of each team based on features. This information is accounted to the trends for victory, then applying supervised learning to predict the results of teams. Moreover, we will use correlations between features to analyze whether the results depend on distinct variables or groups of features. 
## Milestones
### Milestone 1: Preparing and formatting our data for analysis - Week 9
* Collecting and preparing the data
* Preprocessing data
* Transforming data
### Milestone 2: Building model with at least two techniques and evaluate the model - Week 10, 11
* Classifications
* Clustering the best results into groups
* Training a model with two techniques
* Evaluate the model
### Milestone 3: Enhance the performance of our model - Week 12, 13
* Using some methods to enhance performance of the model such as Features Selection, Neural Networks.
