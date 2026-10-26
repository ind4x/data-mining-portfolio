# Lab 03: The "Sunday Effect" Retail Transaction Analysis

This laboratory performs exploratory data analysis (EDA) and rigorous statistical
hypothesis validation on a multi-city retail dataset across Morocco. The objective
is to evaluate whether consumer purchasing dynamics on Sundays diverge significantly
from weekday baselines.

---

## Lab Structure

```text
lab-03-sunday-effect/
├── README.md                          # Technical specification and laboratory overview
├── data/                              # Granular retail transaction datasets
│   ├── data-dictionary.csv            # Variable metadata and semantic specifications
│   ├── retail-synthetic-dataset.csv   # Comprehensive transaction records (3,500+ rows)
│   ├── retail-sundays.csv             # Filtered weekend subset partition
│   └── retail-weekdays.csv            # Filtered weekday baseline partition
├── docs/                              # Empirical visualization deliverables
│   ├── distribution-amounts-plot.png  # Comparative probability density function of basket sizes
│   └── revenue-contribution-plot.png  # Product-level revenue contribution bar chart
└── src/
    └── sunday-effect-analysis.ipynb   # Interactive analysis notebook and statistical tests
```

### File Responsibilities

- **`src/sunday-effect-analysis.ipynb`**: Complete end-to-end data mining notebook performing schema parsing, temporal feature generation, hypothesis formulation, parametric/non-parametric tests, and geo-spatial consistency validation.
- **`data/`**: Transaction datasets covering transactions across Casablanca, Rabat, Fes, Agadir, Marrakech, and Tangier.
- **`docs/`**: Production-ready visualizations highlighting revenue distributions and tech-driven purchase surges.

---

## Architecture & Analytical Findings

```text
+-----------------------+     Temporal Feature Engineering
|  3,500+ Raw Records   |-------------------------------------+
+-----------------------+                                     |
            |                                                 v
            | Statistical Segmentation          +---------------------------+
            +---------------------------------->| Day of Week Partitioning  |
                                                |  - Sunday Cohort          |
                                                |  - Weekday Cohort         |
                                                +---------------------------+
                                                              |
                                                              v
+---------------------------------------------------------------------------+
|                      Hypothesis Testing & Validation                      |
|  - Mean Basket Comparison: Sunday shows +14% value increase (1,120 MAD)   |
|  - Revenue Share: 32% of total Sunday sales driven by 3 tech categories   |
|  - Spatial Stability: Verified across all 6 major Moroccan urban centers  |
+---------------------------------------------------------------------------+
```

---

## Execution Instructions

Launch Jupyter and run the notebook:

```bash
cd lab-03-sunday-effect/src
jupyter notebook sunday-effect-analysis.ipynb
```

---

## Technology Stack

- **Language:** Python 3
- **Data Engineering:** Pandas, NumPy
- **Statistical Analytics:** SciPy
- **Visualization:** Matplotlib, Seaborn

---

## Author

- **Author:** Youssef Fellah ([ind4x_](https://github.com/ind4x))
- **Institution:** Mundiapolis University, Engineering Cycle
