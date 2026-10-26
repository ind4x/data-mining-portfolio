# Lab 04: Bank Marketing Binary Classification Analysis

This laboratory implements a predictive data mining pipeline to model and forecast
client term deposit subscription outcomes based on direct marketing campaign interactions.

---

## Lab Structure

```text
lab-04-bank-marketing/
├── README.md                          # Technical specification and model comparison benchmarks
├── data/                              # Demographic and marketing records
│   └── bank-marketing.csv             # Structured dataset with 4,119 instances and 20 features
└── src/
    └── bank-marketing-analysis.ipynb  # Interactive machine learning pipeline and model evaluations
```

### File Responsibilities

- **`src/bank-marketing-analysis.ipynb`**: Complete executable Python notebook implementing missing data imputation, one-hot categorical encoding, feature standardization, class imbalance mitigation, baseline Logistic Regression, non-linear Decision Trees, and ensemble Random Forest classification.
- **`data/bank-marketing.csv`**: Direct marketing campaign dataset containing customer attributes, economic indices, and binary conversion targets.

---

## Pipeline Architecture & Model Comparison

```text
Raw Marketing Dataset (4,119 samples x 20 features)
                       |
                       v
       +-------------------------------+
       | Preprocessing & Feature Eng.  |
       |  - Mode imputation            |
       |  - One-hot encoding           |
       |  - StandardScaler             |
       +-------------------------------+
                       |
                       +-----------------------+
                       |                       |
                       v                       v
            +---------------------+ +---------------------+
            | Logistic Regression | |    Decision Tree    |
            |     (Baseline)      | |   (Non-linear)      |
            +---------------------+ +---------------------+
                       |                       |
                       +-----------+-----------+
                                   |
                                   v
                      +-------------------------+
                      |   Random Forest Model   |
                      |  (Ensemble Optimization)|
                      +-------------------------+
                                   |
                                   v
             F1-Score & Recall Optimization on Minority Class
```

---

## Execution Instructions

Launch Jupyter and run the notebook:

```bash
cd lab-04-bank-marketing/src
jupyter notebook bank-marketing-analysis.ipynb
```

---

## Technology Stack

- **Language:** Python 3
- **Data Engineering:** Pandas, NumPy
- **Machine Learning:** Scikit-learn (`LogisticRegression`, `DecisionTreeClassifier`, `RandomForestClassifier`, `StandardScaler`, `metrics`)
- **Visualization:** Matplotlib, Seaborn

---

## Author

- **Author:** Youssef Fellah ([ind4x_](https://github.com/ind4x))
- **Institution:** Mundiapolis University, Engineering Cycle
