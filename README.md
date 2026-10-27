# Ensemble Learning and Boosting

This repository organizes the **original Jupyter notebooks supplied for AdaBoost, Gradient Boosting, heterogeneous ensembles (voting and stacking), and XGBoost**. The uploaded notebook files are preserved as supplied, including their cells, code, outputs, metadata, and original execution counts.

## Original notebooks

- [AdaBoost](notebooks/02_AdaBoost_Classification.ipynb) — uploaded as `adaboost.ipynb`.
- [Gradient Boosting Classifier and Regressor](notebooks/03_Gradient_Boosting_Classifier_and_Regressor.ipynb) — uploaded as `gradient_boosting.ipynb`.
- [Voting and Stacking / Heterogeneous Ensembles](notebooks/04_Voting_and_Stacking.ipynb) — uploaded as `ensemble_heterogenous.ipynb`.
- [XGBoost Classification](notebooks/05_XGBoost_Classification.ipynb) — uploaded as `xgboost_classification.ipynb`.

## Repository structure

```text
.
├── notebooks/                 # Original notebooks are preserved unchanged
│   ├── 02_AdaBoost_Classification.ipynb
│   ├── 03_Gradient_Boosting_Classifier_and_Regressor.ipynb
│   ├── 04_Voting_and_Stacking.ipynb
│   ├── 05_XGBoost_Classification.ipynb
│   ├── README.md
│   └── extensions/
│       └── 06_Blending_Classifier_Extension.ipynb
├── concepts/                  # Supplemental concept guides
├── requirements.txt
└── .github/workflows/validate-notebooks.yml
```

## Setup

Install Python 3.10+ and the packages listed in `requirements.txt`:

```bash
python -m pip install -r requirements.txt
jupyter notebook
```

## Concept guides

- [Boosting algorithms](concepts/boosting_algorithms.md)
- [Homogeneous vs. heterogeneous ensembles](concepts/ensemble_types.md)
- [Gradient Boosting parameters](concepts/gradient_boosting_parameters.md)
- [Voting, stacking, and blending](concepts/voting_stacking_blending.md)

## Preservation and validation policy

The four notebooks listed under **Original notebooks** are preserved as supplied. We will not silently correct or rewrite them. Any fixes or extensions will be clearly marked and kept in separate files.

The GitHub Actions workflow validates notebook JSON and structure. It does **not** claim that every original notebook executes successfully; execution errors, if present, should be reviewed and documented separately.

The blending notebook is an additional example created during repository organization, not one of the four files originally uploaded by the user.
