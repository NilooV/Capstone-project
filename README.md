# Mental Health and Economic Analysis

This repository contains Python scripts and Jupyter notebooks for analyzing the relationship between mental health disorders and economic indicators. The analysis is based on a comprehensive dataset of mental health prevalence, GDP, social policies, and mental health workforce statistics.

## Research Questions and Methodologies

### Question 1: How does the GDP of a country correlate with the prevalence of mental health issues?
- **Data Preparation:**
  - Four datasets were cleaned and merged to create `Mental_health_data.csv`.
  - Filtered for high-income countries in 2019, creating `high_income_countries.csv`.
- **Methods:**
  - Correlation calculation between GDP and mental health prevalence rates.
  - Scatter plots and linear regression analysis.

### Question 2: What are the trends in the prevalence of mental health disorders over time in different countries?
- **Data Preparation:**
  - Used `high_income_countries.csv` and selected five countries based on GDP.
  - Merged relevant datasets and saved individual country files.
- **Methods:**
  - Time series plots to visualize trends in mental disorder rates and GDP over time.

### Question 3: How do different mental health approaches correlate with the GDP of countries?
- **Data Preparation:**
  - Merged datasets on mental health approaches and GDP for 2020, creating `merged_cleaned_data.csv`.
- **Methods:**
  - Scatter plots and linear regression analysis for each mental health approach.

### Question 4: Do social policies and the number of psychiatrists influence death rates caused by mental health and substance use disorders?
- **Data Preparation:**
  - Merged datasets on policies, psychiatrist numbers, and death rates for specific years.
- **Methods:**
  - Descriptive analysis, T-tests, permutation tests, and bootstrapping.

### Question 5: Using supervised learning to analyze the relationships between GDP, mental health disorder rates, deaths caused by mental health issues, and the number of psychiatric workers.
- **Data Preparation:**
  - Merged relevant datasets and created a unified dataset `mental_health_data.csv`.
- **Methods:**
  - Applied Linear Regression, Random Forest Regressor, and Gradient-Boosting models.
  - Used k-fold cross-validation and GridSearchCV for model evaluation and tuning.

## Installation

1. **Clone the Repository:**
   ```sh
   git clone https://github.com/your-username/repository-name.git
   cd repository-name
