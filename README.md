# AdCost--RetailMediaCostEstimator

AdCost is a regressor model that predicts the cost of media for a retail food store.

The dataset contains many features and hence feature selection was required. 

Along with regression training this notebook also contains various feature selection techniques used to reduce the dimensionality of the dataset.

The performance of the model includes least of 0.62 RMSE score and a R2score of 99% using Decision Tree with Feature Selection.

Models used:
- Linear Regression
- KNearest Neighbors
- Descision Tree(Final Model)

Feature Selection Techniques includes:
- DT Feature importances
- VIF (variance inflation factor)
- Forward Selection/Backward Elimination
- RFECV
