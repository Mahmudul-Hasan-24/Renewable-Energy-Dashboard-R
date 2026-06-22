# Business Decision Support Using Data-Driven Modeling in R

> Applying decision tree modeling and statistical analysis to support business decisions — built with R, dplyr, ggplot2, and rpart.

---

## Project Overview

This project analyzes real business data to identify the key drivers behind customer decisions and segment customers into actionable groups. The goal is to build a reproducible, data-driven decision support system that translates raw data into clear business recommendations for stakeholders.

**Tools & Technologies:** R · dplyr · ggplot2 · rpart · tidyr · readr

---

## Key Findings

- Identified the **top 3 predictors** driving the target business outcome using decision tree feature importance
- Segmented customers into distinct behavioral groups, enabling targeted marketing and resource allocation
- Decision rules extracted from the model provided clear, actionable recommendations — translating directly into business strategy
- Model evaluated using cross-validation to ensure reliability and avoid overfitting

---

## Analysis Steps

1. **Data Preparation** — Loaded raw business dataset, handled missing values, removed outliers, and engineered KPI features
2. **Exploratory Data Analysis** — Visualized distributions, correlations, and segment patterns using ggplot2
3. **Decision Tree Modeling** — Fitted classification and regression trees using `rpart`; tuned tree depth to balance accuracy and interpretability
4. **Cross-Validation** — Evaluated model performance to ensure generalizability
5. **Stakeholder Dashboard** — Assembled key charts and decision rules into a PowerPoint summary for non-technical stakeholders

---

## Repository Structure

```
├── data/
│   └── dataset.csv                    # Input data
├── R/
│   └── analysis_script.R              # Main analysis script
├── dashboard_presentation.pptx        # Stakeholder-ready summary
└── REPRODUCIBILITY.md                 # Package installation guide
```

---

## How to Run

```r
# Install required packages
install.packages(c("dplyr", "ggplot2", "rpart", "rpart.plot", "readr", "tidyr", "lubridate"))

# Open and run the main script
source("R/analysis_script.R")
```

---

## Skills Demonstrated

- Data cleaning and transformation in R
- Predictive modeling with decision trees
- Business-focused data visualization (ggplot2)
- Communicating analytical findings to non-technical stakeholders

---

## Author

**Mahmudul Hasan,Benjamin, Jürgen**
M.Sc. Computational Social Systems (Business Analytics)
Technical University of Graz & University of Graz
[LinkedIn](https://www.linkedin.com/in/mahmudul-hasan-764307249/) · [GitHub](https://github.com/Mahmudul-Hasan-24)
