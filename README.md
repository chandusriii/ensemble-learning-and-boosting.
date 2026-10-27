# Ensemble Learning and Boosting

This repository collects the **original Jupyter notebooks supplied for AdaBoost, Gradient Boosting, heterogeneous ensemble methods (voting and stacking), and XGBoost**. The four original notebooks are preserved exactly as uploaded. Their cells, source code, order, metadata, and outputs have not been rewritten.

## Original notebooks

- [AdaBoost](notebooks/02_AdaBoost_Classification.ipynb) — original uploaded file `adaboost.ipynb`.
- [Gradient Boosting Classifier and Regressor](notebooks/03_Gradient_Boosting_Classifier_and_Regressor.ipynb) — original uploaded file `gradient_boosting.ipynb`.
- [Heterogeneous Ensembles: Voting and Stacking](notebooks/04_Heterogeneous_Ensembles_Voting_and_Stacking.ipynb) — original uploaded file `ensemble_heterogenous.ipynb`.
- [XGBoost Classification](notebooks/05_XGBoost_Classification.ipynb) — original uploaded file `xgboost_classification.ipynb`.

## Repository layout

```text
.
├── notebooks/          # Original user notebooks, preserved as supplied
├── concepts/           # Supplemental concept guides, separate from notebook code
├── requirements.txt
└── .github/workflows/validate-notebooks.yml
```

## Environment

Install Python 3.10+ and dependencies, then start Jupyter from the repository root:

```bash
python -m pip install -r requirements.txt
jupyter notebook
```

## Important

The notebooks above are preserved as-is. They may contain the user's original conventions or issues. If execution errors are found, document them and put changes in separately named `*_improved.ipynb` copies or explicit follow-up commits. Do not silently edit these original copies.

Blending was not one of the four uploaded notebooks. If added later, it will be labelled clearly as an additional example rather than original user code.
