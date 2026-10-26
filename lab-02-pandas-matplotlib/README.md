# Lab 02: Advanced Data Manipulation and Visualization

This laboratory focuses on engineering robust data transformation and exploratory
visualization workflows using NumPy, Pandas, Matplotlib, and Seaborn.

---

## Lab Structure

```text
lab-02-pandas-matplotlib/
├── README.md                          # Technical specification and laboratory overview
├── data/                              # Benchmark case study datasets
│   ├── movie_scores.csv               # Entertainment ratings and audience reviews
│   ├── office-sales.csv               # Corporate employee sales and salary records
│   └── sample-data-export.csv         # Tabular export baseline for formatting tests
├── docs/                              # Analytical deliverables and figures
│   ├── pandas-matplotlib-report.pdf   # Synthesis report on data manipulation techniques
│   └── salary-vs-sales-plot.jpg       # Multi-variable exploratory scatter and distribution plot
└── src/
    └── pandas-matplotlib-analysis.ipynb # Interactive notebook implementing end-to-end analysis
```

### File Responsibilities

- **`src/pandas-matplotlib-analysis.ipynb`**: Complete executable Python pipeline implementing multidimensional array transformations, dataframe slicing, grouping aggregations, missing value handling, and high-fidelity statistical plotting.
- **`data/`**: Structured tabular data files used as testing inputs for numerical manipulations.
- **`docs/`**: Output visualizations and synthesis report evaluating analytical findings.

---

## Architecture & Data Pipeline

The exploratory analysis pipeline flows through sequential transformations:

```text
Raw Tabular Data (CSV)
         |
         v
+-------------------------------+
| Ingestion & Schema Inspection | ---> pandas.read_csv, dtypes validation, null detection
+-------------------------------+
         |
         v
+-------------------------------+
| Data Cleaning & Normalization | ---> String strip, mode/median imputation, categorical casting
+-------------------------------+
         |
         v
+-------------------------------+
| Aggregations & Pivots         | ---> GroupBy operations, multi-index hierarchies, crosstabs
+-------------------------------+
         |
         v
+-------------------------------+
| Statistical Visualization     | ---> Multi-axis subplots, distribution density, correlation heatmaps
+-------------------------------+
```

---

## Execution Instructions

Launch Jupyter and open the analysis notebook:

```bash
cd lab-02-pandas-matplotlib/src
jupyter notebook pandas-matplotlib-analysis.ipynb
```

---

## Technology Stack

- **Language:** Python 3
- **Numerical Processing:** NumPy
- **Data Engineering:** Pandas
- **Visualization:** Matplotlib, Seaborn
- **Environment:** Jupyter Notebook

---

## Author

- **Author:** Youssef Fellah ([ind4x_](https://github.com/ind4x))
- **Institution:** Mundiapolis University, Engineering Cycle
