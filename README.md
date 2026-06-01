# Simple Linear Regression - Marketing ROI Analysis
## Project Overview
This project analyzes a marketing dataset using  python and ' statsmodels' to build a simple linear regression model.By exploring  correlation metrics and validating OLS regression assumptions, we determine which marketing channel drives the highest Return on Investment(ROI) for sales to guide future budget allocations.
## Key Insights & Findings
* **Top Marketing Channel:**TV Advertising(correlation coefficient:$r\approx 0.9995$)
* **Model Accuracy ($R^2$):**99.9% of sales variance is explained by TV advertising spend.
* **ROI Multiplier:** An estimated increase of **$3.56** in sales revenue generated for every **$1.00** invested in TV.
* **Assumptions Status:** Successfully validated for Linearity, Normality, and Homoscedasticity using residual diagnostic plots.
## Environment Setup & Requirements
To run this notebook locally,ensure you have python 3.8+ installed.
### Environment Setup
Install the required packages by running the following command in your terminal:
...bash
pip install pandas seaborn statsmodels numpy matplotlib scipy
...
## Repository Structure
* 'regression_analysis.ipynb' - Fully executed jupyter Notebook with data cleaning, OLS summary, and plots.
* 'README.md' - Technical  project documentation and stakeholder summary.
