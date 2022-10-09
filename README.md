# Xgboost for Time Series with Lagged Features

## Time Series Forecasing using Gradient Bossting Methods

![plot](img\xgb.png)

This GitHub repo looks at how Xgboost can be used for time series forecasting.

The purpose is to forecast the energy usage for t+1 using two types of features:
- time and date-related features such as hour and day of week. 
- historical values of the energy usage.

The model performance and its predictions for both scenarios are comprehensively analysed. 

The dataset could be download from here [PJMW Hourly](https://www.kaggle.com/code/robikscube/tutorial-time-series-forecasting-with-xgboost/data?select=PJMW_hourly.csv)

![plot](img\preds_Jan_2015.png)

The code also provides some basic steps for data preprocessing as well as variable importance charts.

## Future Work

- [ ] Add pipeline to check the impact of data preprocessing
- [ ] Add other models for benchmarking


## References 
--------------
https://xgboost.readthedocs.io/en/stable/python/python_intro.html

