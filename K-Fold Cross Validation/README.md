## K-Fold Cross-Validation

K-fold cross-validation is a technique used in machine learning to evaluate the performance of a model. It involves splitting the dataset into k equally sized folds, training the model on k-1 folds, and testing it on the remaining fold. This process is repeated k times, with each fold being used as the test set exactly once. The results are then averaged to produce a single performance metric.

### Advantages
- Provides a more accurate estimate of model performance than a single train-test split.
- Reduces the risk of overfitting by using multiple test sets.
- Maximizes the use of available data for training and testing.

### Disadvantages
- Can be computationally expensive, especially for large datasets or complex models.
- Can be sensitive to the choice of k.
- Can be biased if the data is not randomly sampled.

![image](https://github.com/silvanajackoub/ML-Supervised-Learning/assets/99747641/40eced63-6451-4178-9e25-d3dd31185f3c)
