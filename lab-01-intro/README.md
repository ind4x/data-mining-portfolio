# Lab 01: Introduction to Data Mining & CRISP-DM

This laboratory covers foundational methodologies and standard process models in data mining,
centering on the Cross-Industry Standard Process for Data Mining (CRISP-DM) framework.

---

## Lab Structure

```text
lab-01-intro/
├── README.md                          # Laboratory documentation and conceptual overview
└── docs/
    └── intro-methodology-report.pdf   # Comprehensive theoretical and architectural methodology report
```

### File Responsibilities

- **`docs/intro-methodology-report.pdf`**: Technical engineering report formalizing data mining objectives, taxonomy of learning algorithms, data preparation requirements, and validation protocols.

---

## Architecture & Methodology

The study adheres strictly to the iterative six-phase CRISP-DM lifecycle:

```text
+-----------------------+     Feedback Loop
| Business Understanding|<---------------------+
+-----------------------+                      |
            |                                  |
            v                                  |
+-----------------------+                      |
|  Data Understanding   |                      |
+-----------------------+                      |
            |                                  |
            v                                  |
+-----------------------+                      |
|   Data Preparation    |                      |
+-----------------------+                      |
            |                                  |
            v                                  |
+-----------------------+                      |
|       Modeling        |                      |
+-----------------------+                      |
            |                                  |
            v                                  v
+-----------------------+            +-------------------+
|      Evaluation       |----------->|    Deployment     |
+-----------------------+            +-------------------+
```

### Core Methodological Pillars

1. **Taxonomy of Variables:** Discrete vs continuous numerical scales, nominal vs ordinal categorical features, and sparse representation.
2. **Preprocessing Foundations:** Missing data imputation heuristics, outlier detection via interquartile ranges, and feature scaling dynamics (Z-score standardization vs MinMax normalization).
3. **Problem Formulation:** Formal boundary separation between descriptive data mining (clustering, association rules) and predictive data mining (classification, regression).

---

## Technology Stack

- **Methodology:** CRISP-DM Framework
- **Deliverables:** Technical Analytical Report

---

## Author

- **Author:** Youssef Fellah ([ind4x_](https://github.com/ind4x))
- **Institution:** Mundiapolis University, Engineering Cycle
