# Hyperparameter Tuning in Random Forest

Optimizing the performance of a Random Forest model involves tuning various hyperparameters. Two popular methods for hyperparameter tuning are:

### 1. GridSearchCV
GridSearchCV is an exhaustive search over a specified parameter grid. It trains the model on every combination of the hyperparameter grid and selects the best combination based on cross-validation performance.

### 2. RandomSearchCV
RandomSearchCV, on the other hand, performs random combinations of hyperparameters from a specified distribution. This method is faster and more efficient when dealing with large datasets and a high number of hyperparameters.

Both methods help in finding the optimal set of hyperparameters that yield the best model performance.

For a practical demonstration, check out:

- [Hyperparameter Tuning Methods](../notebooks/HypermeterTuningMethods.ipynb)
