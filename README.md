# fifa-23-predictor

This project is built with an aim to implement a machine learning approach to prediction of professional football player's ratings in the next(23rd) edition of the popular "FIFA" football simulation game.

Every player's contribution in the all aspects of the game was analysed over 3 past seasons to determine which factors have the maximum impact on the overall rating for their defending, passing and shooting attributes.

Subsequently, a regression model was trained for predicting the ratings for the next edition of the game(here, FIFA 23) by taking an input of the stats from the season gone by.

The model was then optimised and used to predict the "Defending", "Passing" and "Shooting" stat in the "FIFA 23" game using records from the 2021/22 season gone by.

**The detailed project workflow and description of the process used is given in the ipynb file titled "fifa-23-ratings-predictor.ipynb".
To view a complete list of predicted ratings for each position, check out the "Results" folder.**

Dataset used for the project was taken from the following resources:
1. FBRef Football Statistics Website
2. FUT Bin- FIFA Ratings Website 

The following European clubs were taken into consideration for the project:
1. Manchester United FC(England)
2. Manchester City FC (England)
3. Liverpool FC (England)
4. Chelsea FC (England)
5. Tottenham Hotspur (England)
6. Arsenal FC (England)
7. Real Madrid (Spain)
8. Barcelona (Spain)
9. Atletico Madrid (Spain)
10. Bayern Munich (Germany)
11. Borussia Dortmund (Germany)
12. Juventus (Italy)
13. Inter Milan (Italy)
14. AC Milan (Italy)
15. Paris Saint-Germain (France)

The models used for linear regression include:
1. Simple Linear Regression Model
2. Decision Tree Regressor
3. Bayesian Ridge Regressor
4. K-Nearest Neighbors Regresor

The following Python libraries were used for the implementation of the project:
1. Sci-Kit Learn
2. Matplotlib
3. Pandas and NumPy
4. Seaborn

Through this project, the main objective of building a "FIFA Ratings Predictor" model by exploring different Machine Learning techniques has been accomplished.
The predictions have also been compared to benchmark methods in order to better understand every model's predictive performance.
It has been crucially found out how in-game statistics can be used to predict a professional football player's rating on a simulation game and which factors contribute most towards the same, thus successfully achieving its objective.
