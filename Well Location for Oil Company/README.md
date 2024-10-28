# Выбор локации для скважины добывающей компании

[ipynb](https://github.com/allenbext/Portfolio/blob/main/Well%20Location%20for%20Oil%20Company/Well_Location_for_Oil_Company.ipynb)

## Описание проекта

Необходимо построить модель машинного обучения, которая поможет определить регион, где добыча нефти принесёт наибольшую прибыль компании. Анализ возможной прибыли и рисков выполнены техникой **Bootstrap**.

## Навыки и инструменты

- **python**
- **pandas**
- **matplotlib**
- **seaborn** 
- **numpy**
- sklearn.model_selection.**train_test_split**
- sklearn.model_selection.**GridSearchCV**
- sklearn.preprocessing.**StandardScaler**
- sklearn.preprocessing.**MinMaxScaler**
- sklearn.pipeline.**Pipeline**
- sklearn.compose.**ColumnTransformer**
- sklearn.linear_model.**LinearRegression**
- sklearn.metrics.**root_mean_squared_error**
  sklearn.metrics.**make_scorer**


## Общий вывод

На основе расчитанных техникой Bootstrap на 1000 выборок прибылей и рисков для каждого региона рекомендован определенный регион для разработки. Определен 95 % доверительный интервал.

