# House Prices Advanced Regression

## Overview

We tackled the Kaggle challenge ['House Prices - Advanced Regression Techniques'](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/overview).
It consists of predicting with Machine Learning Regression models the prices of suburbans houses in Ames, Iowa (USA).

## Dataset

Dataset is given by the Kaggle competition. It contains 43 categorical and 36 numerical variables describing the characteristics of residential homes in Ames, Iowa (USA).

The data description file can be found [here](https://github.com/FelipeAvila2/House-prices-Advanced-Regression/blob/main/data_description.txt)

## Main Steps

- Dataset exploration
- Selection of features (for numerical and categorical variables)
- Data cleaning
- Feature engineering
- Trainning + testing the model
- Improving Predictions 
- Final testing

## How to run the code

1. Either clone the repository or download the files
2. Install requirements (requirements.txt)
3. Download the dataset from [Kaggle](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)
4. Open the notebook: House-prices-Advanced-Regression/main.ipynb
5. Run the notebook

## Techniques and tools

- Data visualization : correlation matrix, histograms, scatterplots,bars - [Matplotlib, Seaborn]
- Features tweeking :masked variables, one hot encoding, grouping and new feature creation (Neighborhood mean prices).
- Standardization : StandardScaler 
- PCA (principal component analysis)
- Pycaret
- Random Forest regressor 
- Hyperparameter tuning: gridsearch

## Model

The model that we selected, after doing the Pycaret, was RandomForestRegressor.

### Pycaret

![image](https://user-images.githubusercontent.com/83870535/129350924-0ea894e7-ee4a-42e9-a67f-f29a71a97985.png)


This were the hyperparameters:

- n_estimators=100
- max_leaf_nodes=40
- max_depth=10

### Final score

| Test/Train     | Score       |
| ----------- | ----------- |
| Test  | 0.80       |
| Train | 0.89 |


## About the team

Ironbuddies

Felipe de Ávila Granja 
[Linkedin](https://www.linkedin.com/in/felipedeavilagranja/)
[Kaggle](https://www.kaggle.com/felipedevilagranja)

Luc fley 
[My other projects](https://github.com/luciefley)
