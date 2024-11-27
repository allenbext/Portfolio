# Defining Comment Toxicit

[ipynb](https://github.com/allenbext/Portfolio/blob/main/Defining%20Comment%20Toxicity/Defining_Comment_Toxicity.ipynb)

## Project Description

The store needs a tool that will search for toxic comments and send them for moderation. It is necessary to train a model to classify comments into positive and negative. 

## Skills and Tools

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

## General Conclusion

Based on the results of GridSearch cross-validation, 2 best models with different results and training times were selected. Both models can be recommended for use depending on the key requirements for their indicators.
