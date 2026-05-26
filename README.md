# boston-housing-statistics
Exploratory data analysis and statistical testing on the Boston Housing dataset — includes T-test, ANOVA, Pearson correlation, and linear regression

# Boston Housing Analysis

## Overview
This project analyzes the Boston Housing dataset collected by the U.S. Census Service. 
The goal is to provide actionable insights to housing agency management on the key 
drivers of median home values in Boston, MA.

## Dataset
- **Source:** U.S. Census Service — Boston Housing Prices
- **Records:** 506 census tracts
- **Features:** 14 variables including crime rate, property tax, pupil-teacher ratio, and more

## Project Structure
The analysis is divided into three tasks:

### Task 1 — Dataset Familiarization
- Preview of the dataset
- Data types and shape
- Missing values check
- Duplicate rows check
- Correlation matrix

### Task 2 — Descriptive Statistics & Visualizations
- Descriptive statistics
- Boxplot of median home values (MEDV)
- Bar plot of Charles River proximity (CHAS)
- Boxplot of MEDV by housing age group
- Scatter plot of NOX vs INDUS
- Histogram of pupil-teacher ratio (PTRATIO)

### Task 3 — Statistical Tests
- **Levene's Test** — equality of variances (MEDV by CHAS)
- **Welch's T-test** — difference in MEDV for river vs non-river homes
- **One-Way ANOVA** — MEDV across three housing age groups
- **Pearson Correlation** — relationship between NOX and INDUS
- **Simple Linear Regression** — impact of DIS on MEDV

## Key Findings
| Question | Test | Finding | Significant? |
|---|---|---|---|
| Do river homes cost more? | Welch's T-test | River homes avg ~$6,
