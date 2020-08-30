# Medical Insurance Costs
![GitHub repo size](https://img.shields.io/github/repo-size/rm-kara/Medical-Insurance-Costs)
![GitHub stars](https://img.shields.io/github/stars/rm-kara/Medical-Insurance-Costs)
![GitHub contributors](https://img.shields.io/github/contributors/rm-kara/Medical-Insurance-Costs)
![GitHub forks](https://img.shields.io/github/forks/rm-kara/Medical-Insurance-Costs)

## Project Overview
In this project I analyzed a data set that deals with the **treatment costs of various patients**.  
The data was cleaned using **Pandas** and **Numpy**, visualizations were developed with **Seaborn** and **Matplotlib**.  
Transformational steps such as encoding categorical- and numerical variables were implemented by using Scikit-learn's **Pipeline** module.  
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
To create a new anaconda environment, download [conda_requirements.txt](https://github.com/rm-kara/Medical-Insurance-Costs/blob/master/conda_requirements.txt) and enter the following command:  
```
<conda create --name <env> --file conda_requirements.txt>
```
To install the packages with pip, download [requirements.txt](https://github.com/rm-kara/Medical-Insurance-Costs/blob/master/requirements.txt) and enter the following command:  
```
<pip install -r requirements.txt>
```  
## EDA Highlights

## Model Set up
Lasso, ElasticNet, Linear Regression, LinearRegression, KNeighborsRegressor,GradientBoostingRegressor, DecisionTreeRegressor, RandomForestRegressor  
## Model Performance

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


