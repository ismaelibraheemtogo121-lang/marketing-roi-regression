# # Marketing ROI Regression Analysis
## PDF Report

A complete PDF version of the project is included:

- Marketing_ROI_Regression_Analysis.pdf

The PDF contains all executed code cells, outputs, regression results, visualizations, diagnostic plots, and business recommendations.

## Project Overview

This project uses Simple Linear Regression to analyze the relationship between marketing expenditure and sales performance. The objective is to identify the marketing channel with the strongest influence on sales and provide data-driven recommendations for marketing budget allocation.

## Dataset

The dataset contains the following variables:

* TV Advertising Spend
* Radio Advertising Spend
* Social Media Advertising Spend
* Sales

The dataset was cleaned by handling missing values before analysis.

## Tools and Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Statsmodels

## Installation

Install the required libraries using:

```bash
pip install -r requirements.txt
```

## Analysis Workflow

1. Load and explore the dataset
2. Identify and handle missing values
3. Perform exploratory data analysis (EDA)
4. Calculate correlations between marketing channels and sales
5. Select the most predictive independent variable
6. Build a Simple Linear Regression model using OLS
7. Validate model assumptions using diagnostic plots
8. Interpret model results and provide business recommendations

## Key Findings

* TV advertising exhibited the strongest correlation with Sales (0.9995).
* The Simple Linear Regression model achieved an R-squared value of 0.999.
* The TV advertising coefficient was 3.5615, indicating a strong positive relationship with Sales.
* The model was statistically significant (p < 0.001).

## Recommendation

Based on the analysis, TV advertising should receive the highest priority in future marketing budget allocation. TV advertising demonstrated the strongest relationship with Sales and produced the most statistically significant impact on business performance.

## Repository Contents

* linear_regression.ipynb
* marketing.csv
* requirements.txt
* README.md
