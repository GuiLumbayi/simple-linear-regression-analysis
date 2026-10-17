# 📊 Simple Linear Regression Analysis: Biometric Prediction Modeling

## 🔍 Project Overview
This data science project implements a simple ordinary least squares (OLS) linear regression model to investigate and quantify the relationship between human body measurements. Specifically, the model analyzes how well an individual's **neck size** (predictor variable) can predict their **waist size** (response variable).

This analysis evaluates the strength of the linear trend, calculates key statistical metrics like \(R^2\), and executes residual diagnostics to verify classical regression assumptions.

## 📈 Key Insights & Findings
* **Positive Correlation:** A distinct, linear relationship exists between neck size and waist size. As neck size systematically increases, waist size tends to increase.
* **Model Fit (\(R^2\)):** The calculated Coefficient of Determination is approximately **40.86%**. 
* **Interpretation:** Roughly 40.86% of the overall variability in an individual's waist size can be explained by its linear relationship with their neck size, leaving the remaining variance to be explained by other physiological factors.

## 📁 Repository Contents
* `neck_waist_regression.R`: The complete R script containing exploratory plotting, model estimation, metric calculations, and diagnostic plotting code.
* `README.md`: Project overview and summary documentation.

## 🛠️ Prerequisites & Replication
To run the analysis script locally in RStudio, ensure you have the **`NeckVsWaist`** dataset imported and available within your global workspace environment. 

