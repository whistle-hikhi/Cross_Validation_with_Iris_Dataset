

# Common Types of Cross-Validation:
## 1. K-Fold Cross-Validation:

- The dataset is split into K equally sized subsets (or "folds").
- The model is trained on K-1 folds and tested on the remaining fold.
- This process is repeated K times, each time using a different fold as the test set and the remaining folds for training.
- The average performance across all K trials is computed as the final performance metric.
Commonly used values for K are 5 or 10.

## 2. Leave-One-Out Cross-Validation (LOO-CV):

- A special case of K-fold cross-validation where K is set to the number of samples in the dataset.
- Each sample in the dataset is used once as the test set, and the rest are used for training.
- This can be computationally expensive for large datasets.
