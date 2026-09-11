# kaggle-competitions

Notebooks and write-ups from my Kaggle competitions. Each folder covers one competition with a README, EDA, and modeling notebook.

Kaggle profile: [kaggle.com/rugvedbane](https://www.kaggle.com/rugvedbane)

---

## Competitions

| Season | Competition | Score | Rank | Notes |
|---|---|---|---|---|
| [S6E5](./s6e5-f1-pit-stops/) | F1 Pit Stop Prediction | 0.94793 AUC | Top 55% | First competition |
| [S6E6](./s6e6-stellar-classification/) | Stellar Classification | 0.95548 AUC | Top 71% | XGBoost + early stopping |
| [S6E8](./s6e8-smartphone-addiction/) | Smartphone Addiction | 0.96602 AUC | Top 44% | Optuna + 13 FE features · Bronze Medal |

---

## How This Repo Is Organized

Each folder follows the same structure:

    s6eX-competition-name/
    ├── README.md          # Approach, feature engineering, score breakdown
    ├── eda.ipynb          # Exploratory data analysis
    └── modeling.ipynb     # Preprocessing, modeling, and submission

---

## Stack Used Across Competitions

`Python` · `XGBoost` · `LightGBM` · `CatBoost` · `Optuna` · `scikit-learn` · `pandas` · `seaborn`
