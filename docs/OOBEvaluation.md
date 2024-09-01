# Out-of-Bag (OOB) Evaluation

OOB evaluation is a powerful technique used in ensemble methods like Random Forest to estimate the model's performance.

### What is OOB Evaluation?

When using bootstrap sampling (`bootstrap=True`), some samples are left out of the training dataset for each tree. These "out-of-bag" samples can then be used as a validation set to evaluate the model's performance without the need for a separate validation set.

OOB evaluation provides an unbiased estimate of the model's generalization error and is particularly useful in Random Forest.

To see OOB evaluation in action, access the notebook:

- [OOB Evaluation in Random Forest](../notebooks/OOB-Evaluation.ipynb)
