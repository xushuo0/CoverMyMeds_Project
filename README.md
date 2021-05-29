This is a group project of Erdős Institute 2021 
# CoverMyMeds_Project
### Analysis study group: Zhengchao Wan, Qingsong Wang, Yuda Wang, Shuo Xu

We are dealing with datasets provided by CoverMyMeds which contain a list of drug claims, date of claims and status of PA requests. We use Logistic and random forest models to predict PA approval rates and use SARIMAX model to forecast monthly PA volume.

## Problem description
we mainly focus on these three problems:
1. What drugs are on insurance formulary?
2. What affects PA approval? How to predict a PA outcome?
3. How to predict monthly PA volumes using historical data?



## Exploratory Data Analysis
**pa_frequency.ipynb** is a notebook for exploratory data analysis.
## Predictive Model
### PA approval prediction
**Logistic.ipynb** is a notebook for PA approval prediction via logistic regression with fixed combination of company, drug type and rejection code.
**Logistic regression with time series.ipynb** is a notebook for PA approval prediction via logistic regression .
### Time series study
**exploratory.ipynb** is a notebook for PA volumns prediction via time SARIMAX model.




