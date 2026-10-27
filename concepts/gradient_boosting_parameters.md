# Gradient Boosting Parameters

- `n_estimators`: number of boosting stages. Too few can underfit; too many can overfit and increase training time.
- `learning_rate`: scales each stage's contribution. Lower values often need more estimators.
- `max_depth`: controls individual tree depth and therefore interaction complexity.
- `subsample`: fraction of training examples used per stage; values below 1.0 add stochasticity.
- `loss`: objective optimized by the estimator; the valid choices depend on task and estimator.

Tune hyperparameters using cross-validation on training data. Retain the test set for final evaluation only.
