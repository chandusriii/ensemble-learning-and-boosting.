# Boosting Algorithms

Boosting builds a strong predictor by adding learners in sequence. Later stages are influenced by what the current ensemble still predicts poorly. This differs from bagging, where estimators are trained in parallel on bootstrap samples.

## AdaBoost
AdaBoost adjusts the relative importance of training examples between rounds. Misclassified examples receive greater attention in later rounds. A shallow decision tree with `max_depth=1` is a common weak learner called a decision stump.

Typical parameters:
- `estimator`: base learner.
- `n_estimators`: maximum number of boosting stages.
- `learning_rate`: contribution scale for each stage.

## Gradient Boosting
Gradient Boosting adds learners to reduce a loss function. For common tree-based implementations, each new tree approximates a direction that improves the current model under the chosen loss.

Key parameters include `n_estimators`, `learning_rate`, `max_depth`, `subsample`, and task-dependent `loss`.

## Related algorithms
- **XGBoost:** gradient-boosted trees with regularization and engineering optimizations.
- **LightGBM:** gradient-boosted trees optimized for efficient training on larger datasets.
- **CatBoost:** gradient boosting with particular support for categorical features.
- **HistGradientBoosting** in scikit-learn: histogram-based gradient boosting.

The first two notebooks demonstrate AdaBoost and scikit-learn Gradient Boosting; XGBoost has a separate classification notebook. LightGBM and CatBoost are suggested future extensions, not implementations in this repository yet.
