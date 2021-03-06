# 100 Days of ML Code Log

## Day 0: Oct 30, 2018 

**Progress**: Setting up Git repo, and reading about others who have embarked on this path

## Day 1: Oct 31, 2018

**Progress**: Linear Regression assumptions and their validation
1. Linear relation between features and the dependant variable: Complete
2. Homoscedasticity of error terms: Complete
3. Uncorrelated error terms
4. Independant features

## Day 2: Nov 1, 2018

**Progress**: Linear Regression assumptions and their validation
1. Linear relation between features and the dependant variable: Complete
2. Homoscedasticity of error terms: Complete
3. Uncorrelated error terms: Complete
4. Independant features: Complete

Started: Kaggle - House Prices: Advanced Regression Techniques (Problem #1)

## Day 3: Nov 2, 2018

**Progress**: Data prep for Problem #1
1. Missing value treatment
2. One hot encoding the categorical variables (which leads to much higher number of variables)
3. Principal Component Analysis (to bring down the number of variables, while not losing information)

## Day 4: Nov 3, 2018

**Progress**: PCA for the independant variables
Next Step is to compare two models, PCA based and non-PCA based

## Day 5: Nov 4, 2018
**Progress**: Dependant variable transformation based on Q-Q plot. Busy day, could not get a lot done

## Day 6: Nov 5, 2018
**Progress**
1. Missing value imputation, both categorical and continous variable seperately
2. Skewness check for continous variables
3. Box cox transformation for high skewness variables

## Day 7: Nov 6, 2018
**Progress**: Better understanding the GBM, from https://www.kdnuggets.com/2018/08/unveiling-mathematics-behind-xgboost.html

## Day 8: Nov 7, 2018
**Progress**: Going through another article to understand gradient boosting, https://www.kdnuggets.com/2018/07/intuitive-ensemble-learning-guide-gradient-boosting.html

## Day 9: Nov 8, 2018
**Progress** : Some more reading for in-depth understanding
Linear Regression types: https://www.analyticsvidhya.com/blog/2017/06/a-comprehensive-guide-for-linear-ridge-and-lasso-regression/
Classification Model Measurement: https://towardsdatascience.com/accuracy-precision-recall-or-f1-331fb37c5cb9

## Day 10: Nov 9, 2018
**Progress**: Reading deeper into how GBM works(how splits are created), https://stats.stackexchange.com/questions/162162/relative-variable-importance-for-boosting

## Day 11: Nov 10, 2018
**Progress**: Could not allocate time today due to travel

## Day 12: Nov 11, 2018
**Progress**: Building base models for both PCA and non-PCA dataset, 
1. Lasso
2. ElasticNet
3. Kernel Ridge Regression

## Day 13: Nov 12, 2018
**Progress**: Building first cut model, combining three scores i.e. Lasso, Ridge, ElasticNet, xgboost 

## Day 14: Nov 13, 2018
**Progress**: Some more work on the model, creating feature in the test data to submit on Kaggle 

## Day 15: Nov 14, 2018
**Progress**: More work on the model, to better create the dataset (combining the train and test, while feature engineering)

## Day 16: Nov 15, 2018
**Progress**: First cut of the model ready, only using xgboost

## Day 17: Nov 16, 2018
**Progress**: Model requiring some work to fix output issues

## Day 18: Nov 17, 2018
**Progress**: Further look into the model, and also rebuilding from scratch 

## Day 19: Nov 18, 2018
**Progress**: After fixing the model, using PCA built a Lasso model and made kaggle submission. Current rank: 3821

## Day 20: Nov 19, 2018
**Progress**: With missing value imputation done at each variable level, rank improved by 6 places. Still using ElasticNet

## Day 21: Nov 20, 2018
**Progress**: Experimenting with more individual models, such as Gradient Boosting, Kernel Ridge. Not much improvement

## Day 22: Nov 21, 2018
**Progress**: Understanding how sklearn pipeline works. It would help in combining various models in one go. https://www.kaggle.com/baghern/a-deep-dive-into-sklearn-pipelines

## Day 23: Nov 22, 2018
**Progress**: Break from ML for a day, solving a few coding problems on HackerRank

## Day 24: Nov 23, 2018
**Progress**: Some more algorithms practice on HackerRank

## Day 25: Nov 24, 2018
**Progress**: Learning data structures, and started with practicing Linked Lists
