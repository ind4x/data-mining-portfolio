# Data Mining Laboratory Portfolio

This repository hosts practical implementations, statistical analyses, and
data mining architectures developed for the Data Mining and Business Intelligence
curriculum at Mundiapolis University.

---

## Laboratory Overview

| Laboratory | Domain & Topic | Core Methodology | Primary Deliverables | Reference |
| :--- | :--- | :--- | :--- | :--- |
| **[lab-01-intro](./lab-01-intro)** | CRISP-DM Foundations & Methodology | Theoretical lifecycle, data distributions, preprocessing taxonomy, descriptive vs predictive modeling | Technical Methodology Report | [Report](./lab-01-intro/docs/intro-methodology-report.pdf) |
| **[lab-02-pandas-matplotlib](./lab-02-pandas-matplotlib)** | Exploratory Data Analysis & Visualization | NumPy vectorization, Pandas grouping and filtering, multi-axis statistical plotting (Matplotlib, Seaborn) | Sales & demographic EDA | [Notebook](./lab-02-pandas-matplotlib/src/pandas-matplotlib-analysis.ipynb) |
| **[lab-03-sunday-effect](./lab-03-sunday-effect)** | Statistical Validation & Retail Analytics | Multi-city transactional analysis, temporal feature engineering, basket size hypothesis testing ("Sunday Effect") | Retail discovery study | [Notebook](./lab-03-sunday-effect/src/sunday-effect-analysis.ipynb) |
| **[lab-04-bank-marketing](./lab-04-bank-marketing)** | Predictive Modeling & Imbalanced Classification | Categorical encoding, standard scaling, class imbalance handling, Logistic Regression, Decision Tree, Random Forest | Term deposit classifier | [Notebook](./lab-04-bank-marketing/src/bank-marketing-analysis.ipynb) |

---

## General Running Instructions

### Prerequisites

- **Python:** 3.10 or higher
- **Git**
- **Virtual Environment Tooling:** `venv`

### Setup and Environment

1. **Clone the repository:**
   ```bash
   git clone git@github.com:ind4x/data-mining-portfolio.git
   cd data-mining-portfolio
   ```

2. **Create and activate a virtual environment:**
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   ```

3. **Install dependencies:**
   ```bash
   pip install numpy pandas scikit-learn matplotlib seaborn jupyter
   ```

### Executing Laboratories

Launch Jupyter Notebook from the repository root:

```bash
jupyter notebook
```

Navigate to the `src/` directory in any laboratory folder (`lab-02-pandas-matplotlib`, `lab-03-sunday-effect`, or `lab-04-bank-marketing`) and execute the `.ipynb` notebook.

---

## Technology Stack

- **Language:** Python 3
- **Data Engineering:** NumPy, Pandas
- **Machine Learning & Modeling:** Scikit-learn
- **Data Visualization:** Matplotlib, Seaborn
- **Interactive Development:** Jupyter Notebook

---

## Author

- **Author:** Youssef Fellah ([ind4x_](https://github.com/ind4x))
- **Institution:** Mundiapolis University, Engineering Cycle
