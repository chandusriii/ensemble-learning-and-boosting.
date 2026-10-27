# Voting, Stacking, and Blending

## Voting
Combines predictions using a fixed rule. **Hard voting** selects the majority class; **soft voting** averages class probabilities and selects the largest mean probability. Soft voting requires base classifiers that implement `predict_proba`. Voting regression averages numeric predictions.

## Stacking
Fits a second-level model (the meta-model) to predictions from base estimators. Scikit-learn's stacking estimators use cross-validated predictions to train the meta-model when configured with cross-validation.

## Blending
Reserves a validation holdout. Base models train on one training portion; predictions on the holdout become features for training the meta-model. A separate test set is retained for final evaluation.

| Method | Combination rule | Learns a meta-model? |
|---|---|---|
| Voting | Fixed vote or average | No |
| Stacking | Learns from cross-validated base predictions | Yes |
| Blending | Learns from held-out validation predictions | Yes |

Do not use the final test set to train or tune the meta-model.
