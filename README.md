

# 📊 Data Analysis Projects

This repository contains my data analysis and machine learning projects built using Python and real-world datasets.

---

## 📌 Introduction

Aspiring data analyst with a focus on statistical modeling and real-world data analysis. This repository showcases my projects in data analysis, visualization, and machine learning.

---

## 🚀 Projects

## 📊 Project 1: Sleep Cycle vs Student Performance

### Description
This project analyzes the relationship between sleep patterns and academic performance using statistical techniques.

### Work Done
- Data cleaning and preprocessing  
- Exploratory Data Analysis (EDA)  
- Data visualization using Python  
- Identified patterns between sleep and performance  

### Tools Used
- Python  
- Pandas  
- Matplotlib  

### Outcome
Identified key patterns showing how sleep duration influences academic performance.
---

## 📁 Project 2: Social Media Mood Analysis Dataset

### Description
Designed and published a dataset on Kaggle, collected via Google Forms, to study the impact of social media usage on mood and behavior.

### Dataset Highlights
- Includes demographics, usage patterns, and emotional states  
- Tracks mood before and after social media usage  
- Captures behavioral factors like distraction, relaxation, and comparison  

### Applications
- Data analysis  
- Statistical modeling  
- Machine learning  

---

## 📈 Project 3: Gold & Silver Price Analysis (2020–2026)

### Description
This dataset provides a simulated timeline of monthly gold and silver prices in India for time-series forecasting and analysis.

### Features
- Monthly price data (2020–2026)  
- Simulated market trends and volatility  
- Preprocessed values for machine learning models  

### Use Cases
- Time-series forecasting (ARIMA, regression)  
- Financial data analysis  
- Machine learning practice  

---

## 🔗 Profiles
Kaggle:
https://www.kaggle.com/greatcool

Datasets:
https://www.kaggle.com/datasets/greatcool/social-media-usage-and-its-impact-on-users
https://www.kaggle.com/datasets/greatcool/gold-and-silver-prices-india-2020-2026

Tableau: 
https://public.tableau.com/app/profile/yamini.s8824/viz/PayDiscrimination_17748009371940/Sheet2
https://public.tableau.com/app/profile/yamini.s8824/viz/unhealthy_machines_17747890963580/Dashboard1

---

## 👤 About Me
Integrated M.Sc. Computational Statistics and Data Analytics student at VIT Vellore  
Interested in Machine Learning, Data Analytics, and real-world problem solving

---

## 📊 Sample Output

### Power BI Dashboard – Sleep Cycle vs Student Performance

<img width="1229" height="680" alt="image" src="https://github.com/user-attachments/assets/716afeaf-6775-47e2-962f-528e0a49d6fb" />

---
**📊 Project 4: Heart Attack Risk Prediction & Data Pipeline**
Description
Developed an end-to-end data science pipeline to predict heart attack risks using the UCI Heart Disease dataset . The dataset was taken from kaggle. This project involved transitioning from raw, messy data to a validated predictive model with nearly 80% accuracy.

**Dataset**
https://www.kaggle.com/datasets/imnikhilanand/heart-attack-prediction
---

**Key Technical Contributions:**
**Advanced Data Cleaning:** Handled missing values (represented as '?') by converting them to numeric types and applying mean imputation to maintain dataset integrity.

**Feature Engineering:** Standardized feature scales using StandardScaler to ensure the model was not biased toward variables with larger ranges like Cholesterol levels.

**Predictive Modeling:** Implemented a regression-based approach to estimate heart attack probability, achieving an R² score of 0.38.

**Model Evaluation:** Developed a Confusion Matrix to visualize classification performance, achieving a final Accuracy of 79.6%.

**Visual Analysis:** Created comparative visualizations (Actual vs. Predicted) to identify patterns in model error and variance.
---

**Tech Stack:**

**Languages:** Python

**Libraries**: Pandas, NumPy, Scikit-Learn (Linear Regression, Train-Test Split), Matplotlib, Seaborn

**Tools:** Jupyter Notebook, Git/GitHub
---

**📊 **Project 5: # Synthetic Housing Data & Regression Pipeline**

## Project Overview
This project demonstrates an end-to-end data science workflow, starting from raw mathematical simulation to predictive machine learning modeling. Instead of using a static, pre-existing dataset, this script dynamically generates a **10,000-sample housing market dataset** based on realistic statistical dependencies. It then trains a Linear Regression model to predict property values based on both structural features and geographic constraints.

## Key Components

* **Algorithmic Data Generation:** Generates synthetic features using `numpy` probability distributions. Features include structural variables (`Square_ft`, `Bedrooms`), environmental infrastructure (`Water_Supply`), and geographic tiers (`Location`).
* **Feature Dependency Logic:** Mimics real-world market mechanics by establishing mathematical correlations between variables (e.g., bedroom count directly scales the living area footprint; location dictates the baseline price per square foot).
* **Data Preprocessing & Pipeline:** 
  * Implements **One-Hot Encoding** (`pd.get_dummies`) to translate categorical features into a machine-readable format while utilizing `drop_first=True` to avoid the dummy variable trap.
  * Applies **Standardization** (`StandardScaler`) to scale numeric inputs, ensuring stable model optimization.
* **Predictive Modeling:** Splits the structured data into 70/30 train/test partitions, fits an `sklearn` `LinearRegression` architecture, and evaluates predictive accuracy using $R^2$ Score and Mean Squared Error (MSE).
* **Visual Validation:** Generates a scatter plot mapping Predicted vs. Actual home values against an ideal reference line to visually diagnose model variance and residuals.

## Tech Stack
* **Language:** Python
* **Data Manipulation:** `pandas`, `numpy`
* **Machine Learning:** `scikit-learn`
* **Data Visualization:** `matplotlib`
