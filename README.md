# Ensemble Learning and Boosting

A hands-on learning repository for ensemble learning, boosting algorithms, and model-combination strategies using Python and scikit-learn.

Topics include AdaBoost, Gradient Boosting for classification and regression, XGBoost, homogeneous and heterogeneous ensembles, voting, stacking, and blending.

## Repository structure

- `notebooks/`: runnable Jupyter notebooks for each topic
- `concepts/`: concise concept guides and comparisons
- `.github/workflows/validate-notebooks.yml`: executes notebooks in GitHub Actions
- `requirements.txt`: Python dependencies

## Setup

```bash
python -m venv .venv
# Windows PowerShell
.venv\Scripts\Activate.ps1
# macOS/Linux
# source .venv/bin/activate
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
jupyter notebook
```

## Notebooks

1. [AdaBoost Classification](notebooks/02_AdaBoost_Classification.ipynb)
2. [Gradient Boosting Classifier and Regressor](notebooks/03_Gradient_Boosting_Classifier_and_Regressor.ipynb)
3. [Voting and Stacking](notebooks/04_Voting_and_Stacking.ipynb)
4. [XGBoost Classification](notebooks/05_XGBoost_Classification.ipynb)
5. [Blending Classifier](notebooks/06_Blending_Classifier.ipynb)

## Concept guides

- [Boosting algorithms](concepts/boosting_algorithms.md)
- [Homogeneous vs. heterogeneous ensembles](concepts/ensemble_types.md)
- [Voting, stacking, and blending](concepts/voting_stacking_blending.md)
- [Gradient Boosting parameters](concepts/gradient_boosting_parameters.md)

The notebooks use synthetic datasets for reproducible educational examples. These results should not be interpreted as evidence of real-world model quality. A Novogen Labs-related project can be added separately once its scope and code are ready.
