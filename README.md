# Ensemble Learning and Boosting

A hands-on Python repository for ensemble learning, boosting algorithms, and model-combination methods. It extends the supervised-learning work with focused examples and concept guides.

## Topics
- AdaBoost with a decision-stump base learner
- Gradient Boosting for classification and regression
- XGBoost classification
- Homogeneous vs. heterogeneous ensembles
- Voting, stacking, and blending
- Train/test discipline and task-appropriate evaluation

## Repository structure
```text
.
├── notebooks/
│   ├── 02_AdaBoost_Classification.ipynb
│   ├── 03_Gradient_Boosting_Classifier_and_Regressor.ipynb
│   ├── 04_Voting_and_Stacking.ipynb
│   ├── 05_XGBoost_Classification.ipynb
│   ├── 06_Blending_Classifier.ipynb
│   └── README.md
├── concepts/
│   ├── boosting_algorithms.md
│   ├── ensemble_types.md
│   ├── gradient_boosting_parameters.md
│   └── voting_stacking_blending.md
├── .github/workflows/validate-notebooks.yml
└── requirements.txt
```

## Setup
Python 3.10+ recommended.

```bash
python -m venv .venv
# Windows PowerShell: .venv\Scripts\Activate.ps1
# macOS/Linux: source .venv/bin/activate
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
jupyter notebook
```

## Notebook guide
1. [AdaBoost classification](notebooks/02_AdaBoost_Classification.ipynb)
2. [Gradient Boosting classifier and regressor](notebooks/03_Gradient_Boosting_Classifier_and_Regressor.ipynb)
3. [Voting and stacking](notebooks/04_Voting_and_Stacking.ipynb)
4. [XGBoost classification](notebooks/05_XGBoost_Classification.ipynb)
5. [Blending classifier](notebooks/06_Blending_Classifier.ipynb)

## Concept guides
- [Boosting algorithms](concepts/boosting_algorithms.md)
- [Homogeneous and heterogeneous ensembles](concepts/ensemble_types.md)
- [Voting, stacking, and blending](concepts/voting_stacking_blending.md)
- [Gradient Boosting parameters](concepts/gradient_boosting_parameters.md)

Examples use synthetic datasets for reproducibility. Scores from synthetic data are educational demonstrations, not guarantees of real-world performance. Notebook implementations are organized from the code supplied for this repository; corrections and explanatory additions are called out in context.

A Novogen Labs-related project can be added separately once its scope and code are ready.
