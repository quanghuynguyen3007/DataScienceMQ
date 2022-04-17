# League of Legends
League of Legends is one of the top Multiplayer Online Battle Arena (MOBA) which was developed and publiced by <b>Riot Games</b>. The ultimate goal of team players is how to win the game in which each game divides into two teams which are red and blue teams. The basic principle to win is that which team reaches the base and destroys the nexus faster than the other will end the game whilst defending their own base. However, there are many factors that a team can win a game ranging from blood, baron, dragon to towers, inhibitors. The players stated that these factors mentioned above contributed the most for the winning team.
Source: https://en.wikipedia.org/wiki/League_of_Legends <br>
![League of Legends Champions](/league-of-legends-warriors-season-2020.jpg)
Image_Source: https://selphie1999.weebly.com/lol-league-of-legends-warriors-season-2020-trailer-revealed.html

## Hypothesis
Based on a Kaggle challenge, there are some related questions such as how to win a game, how to predict the outcome, which factors impact the most in the game. <br>
https://www.kaggle.com/bobbyscience/league-of-legends-diamond-ranked-games-10-min/kernels

### Goals:
This repo shows a set of Jupyter Notebooks that we used to answer these question:

+ What factors define a team will win a game.
+ Using distinct methods to predict the outcome of a team in the game.

Therefore, there are two raising questions: what factors or features define a team will win a game of League of Legends and how to use a prediction model to identify what teams will win the game. <br>
__Notice:__ Our group will not use the data set in the Kaggle but use other methods to collect the data on the Internet through Riot API. <br>
Source: https://developer.riotgames.com/apis

## Using Riot API
With a good understanding of Leagued of legend as well as following the kaggle project mentioned above, the team decided to select the 48 most important information for a match. Here are some features according to the correlation. <br>
![Correlation Features ](https://github.com/MQCOMP6200-2020-S1/group-project-group-h/blob/master/LoL_Features.PNG)

## Analysis Techniques
* <b>Linear Regression</b> <br>
__Comment:__ Predict the gold earned and killing which shows that players accumulate gold has a better chance to kill more minions, monsters, etc. <br>
* <b>Logistic Regression</b><br> -- Use some Selection Features to predict the model <br>
* <b>Neural Network by applying TensorFlow </b> <br>-- Enhence the predictive result <br>
* <b>Decision Trees</b> <br>-- Using max_depth=4 <br>
__Note:__ These techniques is nothing new, so the purpose is try to apply basic knowledge to solve problems. 

## Installation:
Requirements:
* Instal Tensorflow in local machine (pip install tensorflow)
* Install Plotly for plotting diagrams (pip install plotly)
