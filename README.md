# 📊 "Business Decision Support-R"

## 📌 Project Overview
This project applies **data-driven decision-making techniques** using R to support business decisions.  
The focus is on:
- Cleaning and transforming raw business data
- Applying decision tree and statistical models
- Creating a dashboard-style summary to communicate insights to stakeholders

---

## 🗂 Repository Structure
```
├── data/
│   └── dataset.csv             # Input data (or link to source)
├── R/
│   └── analysis_script.R       # Main analysis script
├── dashboard_presentation.pptx # Final dashboard-style presentation
└── REPRODUCIBILITY.md          # Instructions for package installation
```

---

## 🔍 Analysis Steps

1. **Data Preparation**
   - Load dataset
   - Handle missing values and outliers
   - Feature engineering (derived KPIs)

2. **Decision Support Modeling**
   - Fit **decision tree models** (classification/regression)
   - Evaluate model accuracy with cross-validation
   - Interpret decision rules for business use

3. **Visualization & Dashboard**
   - Generate key plots (bar charts, histograms, decision tree plots)
   - Assemble findings into **PowerPoint dashboard** for stakeholders

---

## 📊 Key Insights
- Identified top predictors driving target outcome
- Clear segmentation of customer groups for decision-making
- Recommended business actions based on decision rules



---

## 🛠 How to Run Locally

### 1. Open in RStudio
Clone the repository and open `analysis_script.R` in RStudio.

### 2. Install Required Packages
```R
install.packages(c("dplyr","ggplot2","rpart","rpart.plot","readr","tidyr","lubridate"))
```

### 3. Run the Script
Execute all lines in `analysis_script.R` to reproduce results.

### 4. (Optional) Use renv for Reproducibility
```R
install.packages("renv")
renv::init()
renv::snapshot()
```
Commit the `renv.lock` file so others can restore the same package versions.

---

## 📦 Dependencies (R Packages)
- dplyr – data manipulation
- ggplot2 – visualizations
- rpart, rpart.plot – decision tree modeling & plotting
- readr – fast CSV reading
- tidyr – data reshaping
- lubridate – date/time handling

---

## 🚀 Future Improvements
- Automate report generation using RMarkdown
- Deploy interactive dashboard using Shiny
- Add more advanced models (random forest, gradient boosting)

---

## 📜 License
This project is licensed under the MIT License – see [LICENSE](LICENSE) for details.

---

## 👤 Author
**Mahmudul Hasan** ,**Benjamin**, **Jürgen**
 
Master’s of Computational Social System (Business Analytics) at Technical University of  Graz andd University of Graz
