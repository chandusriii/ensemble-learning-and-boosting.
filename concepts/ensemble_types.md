# Homogeneous vs. Heterogeneous Ensembles

## Homogeneous ensemble
Uses base learners from the same algorithm family, often varying samples, random seeds, or parameter settings.

Examples:
- Random Forest: many randomized decision trees.
- Bagging with decision trees.
- Voting among several decision-tree classifiers.

## Heterogeneous ensemble
Combines different model families to benefit from complementary strengths and error patterns.

Examples in this repository:
- Classification: Logistic Regression, Support Vector Classification, and Decision Tree.
- Regression: Linear Regression, Decision Tree Regressor, and Support Vector Regression.

## Important distinction
Homogeneous versus heterogeneous describes the type of base learners. Bagging, voting, and stacking describe ways of building or combining an ensemble. These ideas are related but are not interchangeable labels.
