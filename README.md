# House-Price-Prediction (Regression)
The aim of these project is to predict the house price prediction. Here I have used various Machine Learning Models Like Linear Regression, Random Forest, Adaboost, 	GradientBoosting Regression, XGB Regression, Ensemble Model (Blending Technique).

# Steps in House Price Prediction
1. Loading the dataset
2. Checking Duplicates and Remove them.
3. Target Variable analysis ['Sale Price']
4. Univariat Analysis
   1. Continuous Variables
   2. Catgorical Variables
5. Bi-Variate Analysis
   1. Continuous Variables Vs Target Variables
   2. Categorical Variables Vs Target Variables
   3. Categorical Vs Categorical Analysis
      1. Calculate the Effect size
      2. Chi2 Test
   4. Continuous Vs Continuous Analysis
      1. check Correlation
      2. check Multicolinarity
   5. Continuous Vs Categorical Analysis
      1. Calculate the Effect size ( if the values closer to 0 indicates all categories have similar values, and any single category doesn't have more influence on variable y. and if the values closer to 1 indicates one or more categories have different values than other categories and have more influence on variable y.)
      2. Perform Two-sample z-test and t-test
6. Treat Missing Values
7. Feature Engineering
8. Combine Sparse Class
9. Ordinal Encoding (cols=['ExterQual','ExterCond','BsmtQual','BsmtCond','BsmtExposure','BsmtFinType1',
      'BsmtFinType2','HeatingQC','KitchenQual','FireplaceQu','GarageQual','GarageCond'])
10. Scaled Down the Variables
11. Split the dataset into train test dataset
12. Train the Model using KFold Validation
13. Hyper-parameters Tuning in RandomForest Regressor,AdaBoost, GradientBoosting Regression, XGB Regression
