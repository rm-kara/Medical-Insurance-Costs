# Medical Insurance Costs
![GitHub repo size](https://img.shields.io/github/repo-size/rm-kara/Medical-Insurance-Costs)
![GitHub stars](https://img.shields.io/github/stars/rm-kara/Medical-Insurance-Costs)
![GitHub contributors](https://img.shields.io/github/contributors/rm-kara/Medical-Insurance-Costs)
![GitHub forks](https://img.shields.io/github/forks/rm-kara/Medical-Insurance-Costs)

## Table of contents
* [Project Overview](#project-overview)
* [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installing Requirements](#installing-requirements)
* [EDA Highlights](#eda-highlights)
* [Tested Models](#tested-models)
* [Model Performance](#model-performance)
* [Resources](#resources)

## Project Overview
In this project I analyzed a data set that deals with the **treatment costs of various patients**.  
The data was cleaned using **Pandas** and **Numpy**, visualizations were developed with **Seaborn** and **Matplotlib**.  
Transformational steps such as encoding categorical- and numerical variables were implemented by using Scikit-learn's **Pipeline, StandardScaler, OneHotEncoder and ColumnTransformer** modules.  
Different models were then compared and their performance evaluated using **cross-validation**. Finally, the best model was selected and optimized using **GridSearchCV**.

## Getting Started

### Prerequisites
**Python Version:** 3.7  
**Packages:**
* pandas 1.1.0 
* numpy 1.19.1
* scikit-learn 0.23.2
* matplotlib 3.3.1
* seaborn 0.10.1

### Installing Requirements
To create a new anaconda environment, download [conda_requirements.txt](https://github.com/rm-kara/Medical-Insurance-Costs/blob/master/requirements/conda_requirements.txt) and enter the following command:  
```
<conda create --name <env> --file conda_requirements.txt>
```
To install the packages with pip, download [requirements.txt](https://github.com/rm-kara/Medical-Insurance-Costs/blob/master/requirements/requirements.txt) and enter the following command:  
```
<pip install -r requirements.txt>
```
## EDA Highlights
**Average charges of the different age groups:** 
![alt text](https://github.com/rm-kara/Medical-Insurance-Costs/blob/master/img/charts/Charges-Age-Groups.png "Charges Age Groups")
***
**Charges for Smoker and Non smokers:**
![alt text](https://github.com/rm-kara/Medical-Insurance-Costs/blob/master/img/charts/Smoker-vs-NonSmoker.png "Smokers vs. Non Smokers")
***
**Distribution BMI Categories and their corresponding charges:**
![alt text](https://github.com/rm-kara/Medical-Insurance-Costs/blob/master/img/charts/BMI-Distribution%26Charges.png "BMI Categories & Charges")


## Tested Models
* Lasso
* ElasticNet
* Linear Regression
* KNeighborsRegressor
* GradientBoostingRegressor
* DecisionTreeRegressor
* RandomForestRegressor  

## Model Performance
**Overview of the R2-scores of the different models:**
![alt text](https://github.com/rm-kara/Medical-Insurance-Costs/blob/master/img/charts/Model%20Scores.png "R2 scores")
***
**Results of the final model with tuned Hyperparameters:**
* Best Model's average MAE: 2486.436
* Best Model's average R2: 0.859  
![alt text](https://github.com/rm-kara/Medical-Insurance-Costs/blob/master/img/charts/Model-Predictions.png "Model Predictions")

## Resources
* Link to Data: 
    - [Kaggle Dataset](https://www.kaggle.com/mirichoi0218/insurance)
* BMI Wikipedia: 
    - [BMI Table](https://en.wikipedia.org/wiki/Body_mass_index)
* Visualization: 
    - [Show values in countplot](https://stackoverflow.com/questions/59461033/seaborn-how-to-show-values-in-a-countplot)
* Hyperparameters GradientBoosting:
    - [Boosting Hyperparameters](https://www.datasciencelearner.com/gradient-boosting-hyperparameters-tuning/)
    - [More on tuning Hyperparameters](https://educationalresearchtechniques.com/2019/01/14/gradient-boosting-regression-in-python/)


