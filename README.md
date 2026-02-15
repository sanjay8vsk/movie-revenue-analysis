# 🎬 Movie Revenue Analysis  
End-to-End Data Science Project | Regression Modeling | Feature Importance

---

## 📌 Project Overview

This project analyzes which features most strongly influence global box-office revenue using a structured end-to-end data science workflow.

The objective was not only to build predictive models, but also to demonstrate:

- Data preparation & feature engineering  
- Exploratory data analysis (EDA)  
- Model comparison & evaluation  
- Interpretation of results  
- Critical reflection on assumptions & limitations  

---

## 🎯 Research Question

**Which movie features most strongly influence global box-office revenue?**

---

## 📊 Dataset

- Source: Kaggle – Movie Dataset for Analytics & Visualization  
- Size: ~1,000,000 records  
- Type: Synthetic but realistic  
- Features include:
  - Financial variables (Budget, Opening Day, One Week Sales, Revenue)
  - Engagement metrics (IMDb votes, Rotten Tomatoes votes)
  - Categorical features (Genre, Director, Lead Actor)
  - Release information (Release Date)

> ⚠️ Note: The dataset is synthetic and used for analytical demonstration purposes.

The dataset is not included in this repository due to size constraints.  
It can be downloaded directly from Kaggle.

---

## 🧹 Data Preparation

- Removed duplicates  
- Checked for missing values  
- Converted `ReleaseDate` to datetime  
- Extracted:
  - Release Year
  - Release Month
  - Release Day
- Created:
  - Movie Age
  - ROI (Return on Investment)
- Handled high-cardinality categorical variables

Each step was performed to improve data quality and modeling reliability.

---

## 📈 Exploratory Data Analysis (EDA)

Key analyses included:

- Budget vs Revenue relationship  
- Opening Day / One Week Sales vs Revenue  
- Genre distribution  
- Release trends across years  

EDA insights guided feature selection and modeling decisions.

---

## 🤖 Modeling Approach

Since revenue is a continuous variable, regression models were used.

### Models Implemented:
- Linear Regression (baseline)
- Ridge Regression
- Lasso Regression
- Random Forest Regressor

### Evaluation Metrics:
- R² Score
- MAE (Mean Absolute Error)
- MSE (Mean Squared Error)

Random Forest was selected for final interpretation due to its ability to capture non-linear interactions and provide reliable feature importance.

---

## 🔍 Key Findings

The strongest predictors of movie revenue were:

- One-Week Sales  
- Opening-Day Sales  
- Production Budget  

Engagement metrics and categorical features had comparatively smaller influence.

---

## ⚠️ Limitations & Critical Reflection

- The dataset is synthetic; patterns may be cleaner than real-world data.
- Monetary values were not adjusted for inflation, which may bias cross-decade comparisons.
- High model accuracy likely reflects controlled synthetic relationships.

This project demonstrates the data science workflow rather than real-world financial forecasting performance.

---

## 🧠 Key Learnings

This project strengthened my ability to:

- Work with large datasets (1M+ records)
- Engineer meaningful features
- Compare multiple regression models
- Handle computational constraints
- Interpret model performance critically
- Communicate assumptions and limitations clearly

---

## ⚙️ Installation

1. Clone the repository:
