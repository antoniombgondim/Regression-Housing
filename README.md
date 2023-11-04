# Regression-Housing
The features address to houses characteristics of an area in California
Clearly, the median_house_value is correlated with some other features, e.g., median_income and location
Thus, we can estimate median_house_value = regression_model(median_income, longitude, latitude, ...)
The taks is to build regressors to predict median_house_value using the other features
If you need some motivation to do this task, see this
Dataset on https://www.kaggle.com/c/zillow-prize-1 ($1,200,000)

XGBoost, RandomForestRegressor are fitted and parameters are estimated, along with the accuracies.
