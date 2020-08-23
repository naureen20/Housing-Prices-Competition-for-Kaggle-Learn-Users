# Predicting Housing prices using Advanced Regression Technique  
  ## Objective is to perform a detailed EDA and estimate House prices using Ensemble technique.
  
Applying the learnings in the Machine Learning course, Detailed **exploratory data analysis** and various **Advanced regression models XG-Boost, Ridge, Lasso, Elastic-net, Gradient Boost, SVR are employed.**

  STEPS 2 to 5 are for exploratory data analysis.
  
  
Predicting Sales Price of a given house in real estate market using various statistical analysis tools. Obtained the closest price that a client might sell their house utilizing machine learning.
*Presented in the form of iPython Notebooks.*

Data is extracted from [Kaggle](https://www.kaggle.com/c/home-data-for-ml-course/data)
Running code file can be found [Here](https://www.kaggle.com/naureenmohammad/house-price-all-regression-models-final)

## Contents

> 1. <a href='https://github.com/naureen20/Housing-Prices-Prediction-with-Advanced-Regression-models/blob/master/house%20price%20all%20regression%20models_.ipynb#1. Loading and Exploring Data'>Loading and Exploring Data</a>

  Data is read from files and SalesPrice in training dara, ID for houses in test data are located
 
 
 ### Exploratory Data Analysis
 
>2. <a href='https://github.com/naureen20/Housing-Prices-Prediction-with-Advanced-Regression-models/blob/master/house%20price%20all%20regression%20models_.ipynb#step2'>Cleanup of data and Handling missing values</a>

  Many categorical features hold ratings which can be converted into numbers and missing values can be taken as 0. 
  
>3. <a href='https://github.com/naureen20/Housing-Prices-Prediction-with-Advanced-Regression-models/blob/master/house%20price%20all%20regression%20models_.ipynb#step3'>Analyzing Features having Object data type</a>

  Handling missing values manually and eliminating features with majority missing values
  
>4. <a href='https://github.com/naureen20/Housing-Prices-Prediction-with-Advanced-Regression-models/blob/master/house%20price%20all%20regression%20models_.ipynb#step4'>Analyzing non-Categorical Features</a>

  Handling missing values manually by looking at features having close correlation with them and looking for possible collinearity and making new features from available features that have better correlation with Target prediction.
  
>5. <a href='https://github.com/naureen20/Housing-Prices-Prediction-with-Advanced-Regression-models/blob/master/house%20price%20all%20regression%20models_.ipynb#step5'>Feature Engineering and EDA</a>
  
  Imputing if there are any remaining missing values, looking for outliers, skewness, observing feature importances and analysing correlation between each category of features together 

### Advanced Regression Models

6. <a href='https://github.com/naureen20/Housing-Prices-Prediction-with-Advanced-Regression-models/blob/master/house%20price%20all%20regression%20models_.ipynb#step6'>Creating Models with Grid Search</a>

  Ridge regression, Lasso regression, ElasticNet, XGBoost,SVR, Gradient Boost Regression models have been formed with Grid search for Best Hyper Parameters. Stacking all models and using XGBoost for 2nd level training improved accuracy of predictions. 
  
  
### Ensemble   

7. <a href='https://github.com/naureen20/Housing-Prices-Prediction-with-Advanced-Regression-models/blob/master/house%20price%20all%20regression%20models_.ipynb#step7'>Ensembling and Obtaining result</a>

  For improving accuracy, all trained model predictions are Weight Averaged with most weightage for Stacking to obtain a Ensembled prediction of Sales Price

8. <a href='https://github.com/naureen20/Housing-Prices-Prediction-with-Advanced-Regression-models/blob/master/house%20price%20all%20regression%20models_.ipynb#step8'>References</a>

  * [Kaggle Blend and stack models](https://www.kaggle.com/itslek/blend-stack-lr-gb-0-10649-house-prices-v57)
  * [Kaggle Detailed EDA](https://www.kaggle.com/erikbruin/house-prices-lasso-xgboost-and-a-detailed-eda)
