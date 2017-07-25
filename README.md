## Predicting House Sales Prices Using Advanced Regression Techniques

This project was based on a Kaggle competition: https://www.kaggle.com/c/house-prices-advanced-regression-techniques

The goal for this project is to practice on feature engineering, data EDA,  using machine learning regression techniques to select best prediction model for home sales prices. 

The dataset I used consisted of 79 variables describing features of homes in Ames, Iowa.

I used Numpy, Pandas, and Seaborn plots for exploratory data analysis and data cleaning.

From the scikit-learn library, I built a series of grid-searched k-neighbors, tree-based, linear regression models to try to improve my predictive accuracy.

My best model which gives the highest test score is "Random Forest Regressor" with below parameters:

          bootstrap=True, criterion='mse', max_depth=None,
           max_features='auto', max_leaf_nodes=None,
           min_impurity_split=1e-07, min_samples_leaf=1,
           min_samples_split=2, min_weight_fraction_leaf=0.0,
           n_estimators=28, n_jobs=1, oob_score=False, random_state=42
          
          
I've conducted a 
          Train_Score: 0.97292543997
          Test_Score: 0.888000886093
on the "train.csv" dataset

