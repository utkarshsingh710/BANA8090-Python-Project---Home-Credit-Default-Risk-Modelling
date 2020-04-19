1. Link to kaggle datasets used for the project: https://www.kaggle.com/c/home-credit-default-risk/data

2. Datasets were downloaded using the kaggle API

2. Not all datasets have been used for the project. Overall 5 datasets have been used for feature engineering.I have used the following: static header data (Apptrain), Bureau data on loans (2 datasets), Past instalments payments data, Previous Applications data

3. i)3 logistic regression models are built: 1 in the feature selection step, and 2 for model training
   ii) 3 non-linear models are used: 1 Random Forest Classifier in the feature selection step, 1 xgboost model for prediction, 1 Neural Network (stacked using Keras) for prediction

4. All steps are in the "_vFinal" ipynb file 
   