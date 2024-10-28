# Определение токсичности комментариев

[ipynb](https://github.com/allenbext/Portfolio/blob/main/Defining%20Comment%20Toxicity/Defining_Comment_Toxicity.ipynb)

## Описание проекта

Магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию. Требуется обучить модель классифицировать комментарии на позитивные и негативные. 

## Навыки и инструменты

- **python**
- **pandas** 
- **numpy**
- **spacy**
- **nltk**
- **tdqm**
- sklearn.feature_extraction.text.**TfidfVectorizer**
- sklearn.pipeline.**Pipeline**
- sklearn.model_selection.**train_test_split**
- sklearn.model_selection.**GridSearchCV**
- sklearn.linear_model.**LogisticRegression**
- sklearn.metrics.**make_scorer**
- sklearn.metrics.**f1_score**
- catboost.**CatBoostClassifier**

## Общий вывод

По результатам работы GridSearch на кросс-валидации выбраны 2 лучшие модели с различными результамами и временем обучения. Обе модели могут быть рекомендованы к использованию в зависимости от ключевых требований к их показателям.
