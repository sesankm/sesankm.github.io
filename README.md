###  Sesank M - Data Science Portfolio

## [Project 1: Stock Price Forecasting](https://github.com/sesankm/stock_price_prediction)
* developed a tool for stock price forecasting
* used yahoo_fin package to fetch historical price data
* engineered features, and calculated technical indicators like moving averages
* optimized bagging regressor with GridSearchCV to predict stock prices with MAE of 15.85
![](/images/google_price_chart.png)

## [Project 2: Bank Deposits Prediction](https://github.com/sesankm/bank_deposit_prediction)
* built a model to identify potential clientele for banks
* determines which individuals in a demographic are most likely to make a bank deposit
* optimized decision tree clasifer (MSE=0.23) and random forest classifer (MSE=0.15) with grid search cv
* built neural network to test against decision tree and random forest classifiers (MSE=0.16)
![](/images/jobs_plot.png)

## [Project 3: House Value Estimator](https://github.com/sesankm/house_price_prediction)
* a tool which etimates the value of a home
* scraped texas housing data from homefinder.com
* engineered features and reduced noise in the data
* optmized linear regression model (R2=.65), bagging regressor (R2=.97) and random forest regressor (R2=.99)<br>
![](/images/dist1.png)
![](/images/dist2.png)

## [Project 4: Diabetes Prediction](https://github.com/sesankm/diabetes_prediction)
* predict risk of diabetes
* tested support vector machine, ridge classifier and neural network models
* engineered features to improve model performance
* Model Performance:
  * <strong>SVC</strong>: MSE=.09
  * <strong>Ridge Classifier</strong>: MSE=.09
  * <strong>Neural Network</strong>: MSE=.07
![](/images/age_dist.png)
![](/images/gender.png)

## [Project 5: Songs Recommender](https://github.com/sesankm/song_recommender)
* a content-based filtering recommendation system which recommend songs
* scraped genius.com to find songs with similar writers, producers and engineers
* built an api with flask and productionized project with heroku
