# Predicting taxi orders for the next hour (time series)

[ipynb (en)](https://github.com/allenbext/Portfolio/blob/main/Predicting%20customer%20churn%20for%20a%20telecom%20operator/Predicting_customer_churn_for_a_telecom_operator_(en).ipynb)  
[ipynb (ru)](https://github.com/allenbext/Portfolio/blob/main/Predicting%20customer%20churn%20for%20a%20telecom%20operator/Predicting_customer_churn_for_a_telecom_operator_(ru).ipynb)  

## Project Description

A taxi company has collected historical data on taxi orders at airports. To provide more drivers during peak periods, it needs to forecast the number of taxi orders for the next hour.

## Skills and Tools

- **python**
- **pandas**
- **matplotlib**
- statsmodels.tsa.seasonal.**seasonal_decompose**
- statsmodels.tsa.stattools.**adfuller**
- sklearn.model_selection.**train_test_split**
- sklearn.model_selection.**GridSearchCV**
- sklearn.model_selection.**TimeSeriesSplit**
- sklearn.pipeline.**Pipeline**
- sklearn.preprocessing.**FunctionTransformer**
- sklearn.linear_model.**LinearRegression**
- sklearn.metrics.**root_mean_squared_error**
- catboost.**CatBoostClassifier**
  

## General Conclusion

A model was developed that predicts taxi orders for the next hour. A visualization of the comparison of true values ​​and predictions shows that, overall, the model captures hourly fluctuations in taxi demand. The best model has been successfully tested for adequacy, and the quality metric of the best model exceeds the quality metrics of the models that were not trained.
