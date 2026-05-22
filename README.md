# Marketing Sales Analysis and Linear Regression Modeling

## Project Overview

This project analyzes marketing expenditure across multiple promotional channels and investigates their relationship with sales performance using exploratory data analysis (EDA) and simple linear regression.

The objective of this study is to identify whether marketing investment patterns contribute to measurable changes in sales outcomes and to evaluate the strength of those relationships using statistical modeling techniques.

---

## Project Objectives

- Explore the structure and quality of the dataset
- Perform data cleaning and preprocessing
- Analyze numerical feature distributions
- Investigate relationships between marketing channels and sales
- Develop a simple linear regression model
- Evaluate regression assumptions using diagnostic analysis

---

## Dataset Information

This project uses the **Marketing Sales Dataset (`marketing_sales_data.csv`)**, a fictional dataset created for analytical and educational purposes and adapted from a Kaggle source.

The dataset represents spending across different promotional channels and corresponding sales outcomes.

### Dataset Summary

| Attribute | Details |
|----------|----------|
| Dataset Name | Marketing Sales Dataset |
| Number of Records | 572 |
| Number of Features | 5 |
| Source | Modified Kaggle Dataset |

---

## Data Dictionary

| Column | Type | Description |
|--------|------|-------------|
| TV | string | Television promotion budget category (Low, Medium, High) |
| Radio | integer | Radio promotion budget (millions) |
| Social Media | integer | Social media promotion budget (millions) |
| Influencer | string | Influencer category (Mega, Macro, Nano, Micro) |
| Sales | integer | Total sales generated (millions) |

---

## Methodology

### Data Preparation
- Loaded and inspected the dataset
- Identified and removed missing values
- Selected numerical features for analysis

### Exploratory Data Analysis
- Distribution analysis using histograms
- Outlier analysis using boxplots
- Pairwise relationship analysis
- Correlation exploration

### Statistical Modeling
A simple linear regression model was developed using:

\[
Sales = \beta_0 + \beta_1(Radio)
\]

### Model Diagnostics
Regression assumptions were evaluated through:

- Residual distribution analysis
- Q–Q Plot assessment
- Residual vs fitted visualization

---

## Key Findings

- Radio promotion budget showed a strong positive relationship with sales
- The regression model achieved an **R² score of 0.757**
- Approximately **75.7% of the variation in sales** was explained by radio promotion spending
- The predictor variable was statistically significant

Regression Equation:

\[
Sales = 8.17(Radio) + 41.53
\]

Interpretation:

For every additional **1 million invested in radio promotion**, predicted sales increase by approximately **8.17 million** on average.

---

## Repository Structure

```text
datasets/
│
notebooks/
│
outputs/
│
README.md
```

---

## Technologies Used

- Python
- Pandas
- Seaborn
- Matplotlib
- Statsmodels
- Quarto

---

## Conclusion

This analysis demonstrates that marketing expenditure—particularly radio promotion—shows a strong positive association with sales performance.

Through exploratory analysis and statistical modeling, the project quantified this relationship and evaluated model reliability using regression diagnostics.

The results suggest that radio promotion expenditure serves as a meaningful predictor of sales within this dataset.

---

## Author

Udit Kidiyoor
