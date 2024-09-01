# Hyperparameters in Random Forest

Random Forest has several hyperparameters that you can tune to optimize the model's performance. These hyperparameters can be categorized into three groups:

### Part 1: Random Forest Specific Parameters
- **`n_estimators`**: The number of decision trees in the forest.
- **`bootstrap`**: Determines whether bootstrap samples are used when building trees. If set to `False`, the whole dataset is used for each tree without replacement.

### Part 2: Decision Tree Parameters
- **`max_depth`**: The maximum depth of the tree.
- **`min_samples_split`**: The minimum number of samples required to split an internal node.
- **`min_samples_leaf`**: The minimum number of samples required to be at a leaf node.

### Part 3: General Hyperparameters
- **`max_features`**: The number of features to consider when looking for the best split.
- **`max_samples`**: The number of samples to draw from the dataset to train each tree.

For further reference, check out the official Scikit-Learn documentation:

- [RandomForestClassifier Documentation](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html)
- [RandomForestRegressor Documentation](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html)
