###  Sesank M - Data Science Portfolio

## [Project 1: Stock Price Forecasting](https://github.com/sesankm/stock_price_prediction)
* developed a tool for stock price forecasting
* used yahoo_fin package to fetch historical price data
* engineered features, and calculated technical indicators like moving averages
* optimized bagging regressor with GridSearchCV
* Model Performance <br>
<strong>Linear Regression</strong>: Negative MAE=-43.88 <br>
<strong>AdaBoost Regressor</strong>: MAE=33.16<br>
<strong>Bagging Regressor</strong>: MAE=15.85<br>
<strong>Random Forest Regressor</strong> MAE=16.27<br>

![](/images/google_price_chart.png)

## [Project 2: Bank Deposits Prediction](https://github.com/sesankm/bank_deposit_prediction)
* built a model to identify potential clientele for banks
* determines which individuals in a demographic are most likely to make a bank deposit
* optimized decision tree clasifer (MSE=0.23) and random forest classifer (MSE=0.15) with grid search cv
* built neural network to test against decision tree and random forest classifiers (MSE=0.16)
* Model Performance <br>
<strong> Decision tree: </strong> MSE=0.23 <br>
<strong> Random Forest: </strong> MSE=0.15 <br>
<strong> Neural Network: </strong> MSE=0.16 <br>

![](/images/jobs_plot.png)

## [Project 3: House Value Estimator](https://github.com/sesankm/house_price_prediction)
* a tool which etimates the value of a home
* scraped texas housing data from homefinder.com
* engineered features and reduced noise in the data
* Model Performance <br>
<strong>Linear Regression</strong>: R2=.65 <br>
<strong>Bagging Regressor</strong>: R2=.97 <br>
<strong>Random Forest Regressor</strong>: R2=.99 <br>

![](/images/dist1.png)
![](/images/dist2.png)

## [Project 4: Handwritten Digit Recognizer](https://github.com/sesankm/digit_recognizer)
* Handwritten digit recognizer with keras and tensorflow
* Model Performance: 96% Accuracy on validation data

![](/images/digit_predictions.png)

## [Project 5: Diabetes Prediction](https://github.com/sesankm/diabetes_prediction)
* predict risk of diabetes
* tested support vector machine, ridge classifier and neural network models
* engineered features to improve model performance
* Model Performance: <br>
<strong>SVC</strong>: MSE=.09 <br>
<strong>Ridge Classifier</strong>: MSE=.09 <br>
<strong>Neural Network</strong>: MSE=.07 <br>

![](/images/diabetes_age_dist.png)
![](/images/gender.png)

## [Project 6: Songs Recommender](https://github.com/sesankm/song_recommender)
* a content-based filtering recommendation system which recommend songs
* scraped genius.com to find songs with similar writers, producers and engineers
* built an api with flask and productionized project with heroku

## [Project 7: Article Summarizer](https://github.com/sesankm/article_summarizer)
* a tool which finds latest news about companies and summarizes articles
* scraped news articles from reuters with BeautifulSoup
* summarized articles with spaCy
