# Bagging vs. Random Forest

### What is Bagging?

Bagging, or Bootstrap Aggregating, is a general ensemble technique that involves training multiple models on different random subsets of the data and then aggregating their predictions. While Random Forest is a specific type of bagging that uses decision trees as base models, bagging can also be applied to other algorithms like K-Nearest Neighbors (KNN) or Support Vector Machines (SVM).

### Key Differences

1. **Base Models**:
   - **Bagging**: Can use any model as the base, such as KNN, SVM, etc.
   - **Random Forest**: Always uses decision trees as the base models.

2. **Feature Sampling**:
   - **Bagging**: Generally involves tree-level sampling, where the selected features are the same across all nodes.
   - **Random Forest**: Utilizes node-level feature sampling, where each node selects a new random subset of features.

This difference in feature sampling typically makes Random Forest more robust and effective compared to standard bagging with decision trees.

For a practical comparison, refer to the notebook:

- [Bagging vs. Random Forest](../notebooks/Bagging-vs-RandomForest.ipynb)
