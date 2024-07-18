<h1>Portfolio Optimization Case Study</h1>

<h2>Project Overview</h2>
In this case study, we explore the construction and optimization of investment portfolios using stocks and ETFs. The goal is to demonstrate the process of creating a portfolio with equal weighting and another portfolio optimized for the best return adjusted for risk. This project involves the following steps:

- <b>Data Import: Importing five years of historical data for 15 stocks and ETFs from the NASDAQ database. </b>

Data Import: <br/>
<img src="https://imgur.com/3KFpAY6.png" height="70%" width="70%" alt="Portfolio Optimization"/>
<br />

- <b>Initial Portfolio Construction: Building an initial portfolio with equal weighting for each of the 15 stocks. </b>

Portfolio Construction: <br/>
<img src="https://imgur.com/GpHDfrm.png" height="70%" width="70%" alt="Portfolio Optimization"/>
<br />

- <b>Analysis and Visualization: Analyzing and visualizing the performance of the equal-weighted portfolio. </b>

Visualizing the performance of the equal-weighted portfolio: <br/>
<img src="https://imgur.com/JwKHekf.png" height="70%" width="70%" alt="Portfolio Optimization"/>
<br />

- <b>Scenario Generation: Generating 10,000 portfolio scenarios with random weightings for each stock. </b>
- <b>Optimization: Identifying the optimal portfolio from the generated scenarios and visualizing the results. </b>

Portfolio with the best risk-adjusted return: <br/>
<img src="https://imgur.com/RVyO9GO.png" height="70%" width="70%" alt="Portfolio Optimization"/>
<br />

<h2>Key Components</h2>

- <b>Data Handling: The project utilizes historical stock price data, focusing on the adjusted closing prices for analysis. </b>
- <b>Equal-Weighted Portfolio: The initial portfolio is constructed with equal allocation to each stock, serving as a baseline for comparison. </b>

Equal-Weighted Portfolio: <br/>
<img src="https://imgur.com/f2dIsvC.png" height="70%" width="70%" alt="Portfolio Optimization"/>
<br />

Correlation Matrix: <br/>
<img src="https://imgur.com/ej6JEY8.png" height="70%" width="70%" alt="Portfolio Optimization"/>
<br />

- <b>Scenario Analysis: Using Monte Carlo simulation, 10,000 different portfolio weight combinations are generated to explore a wide range of potential outcomes. </b>
- <b>Optimization Technique: The project employs optimization techniques to identify the portfolio with the best risk-adjusted return. </b>

Identifying the optimal portfolio: <br/>
<img src="https://imgur.com/ueEnOtR.png" height="70%" width="70%" alt="Portfolio Optimization"/>
<br />

- <b>Visualization: Comprehensive visualizations are created to illustrate the performance and characteristics of both the equal-weighted and optimized portfolios.</b>

<h2>Project Structure</h2>

- <b>Import Packages & Data: The initial setup, including the import of necessary Python packages and data. </b>
- <b>Data Processing: Steps to clean and prepare the data for analysis. </b>
- <b>Portfolio Construction: Building the equal-weighted portfolio. </b>
- <b>Scenario Generation and Optimization: Generating random portfolios and optimizing for the best return adjusted for risk. </b>
- <b>Results Visualization: Graphical representation of the portfolio performances and optimization results.</b>

<h2>How to Use </h2>

To run this project, you need to have Python installed along with the following packages:
- <b>Pandas </b> 
- <b>numpy </b>
- <b>seaborn </b>
- <b>matplotlib </b>

You can execute the Jupyter notebook step by step to see the data import, processing, portfolio construction, scenario generation, optimization, and visualization processes in action.

<h2>Purpose and Conclusion </h2>
This project provides a comprehensive demonstration of portfolio optimization, showcasing the steps from data import and processing to scenario analysis and optimization. It serves as a valuable resource for understanding the intricacies of portfolio management and optimization techniques in the financial services industry. THIS ANALYSIS ALONE CANNOT BE USED BY FINANCIAL ANALYSTS, INVESTORS, AND DECISION-MAKERS TO MAKE AN INVESTMENT DECISION.
<br />





# Credit Risk Analysis Project

## Overview
This project aims to predict loan default risk using machine learning techniques. The analysis is divided into three main stages:
1. Data Preprocessing and Exploratory Data Analysis (EDA)
2. Logistic Regression Model Implementation
3. Random Forest Model Implementation

The project utilizes a dataset containing various features related to loan applications and borrower information.

## Notebooks

### 1. Credit Risk Analysis - 1.ipynb
This notebook lays the groundwork for the credit risk analysis. It involves:
- Loading the dataset (`credit_risk_dataset_feat.csv`).
- Cleaning the data and engineering features.
- Conducting exploratory data analysis to gain insights into the data.
- Splitting the dataset into training and testing sets.

### 2. Credit Risk Analysis - Logistic Regression.ipynb
This notebook focuses on building and evaluating a logistic regression model. Key steps include:
- Using the preprocessed data from the first notebook.
- Training a logistic regression model to predict loan defaults.
- Evaluating the model's performance using metrics such as accuracy, precision, recall, and ROC-AUC.
- Visualizing the results to interpret the model's performance.

### 3. Credit Risk Analysis - Random Forest.ipynb
This notebook explores the use of a random forest model for predicting loan defaults. It covers:
- Using the preprocessed data from the first notebook.
- Training a random forest classifier.
- Evaluating the model's performance and comparing it with the logistic regression model.
- Visualizing feature importance to understand the impact of different features on the prediction.

## Key Findings
- Both logistic regression and random forest models provide insights into factors influencing loan defaults.
- The random forest model generally offers better performance and robustness compared to the logistic regression model.
- Feature importance analysis helps in understanding the key predictors of loan default risk.

## Conclusion
This project demonstrates the application of machine learning techniques in the financial services industry, specifically for credit risk analysis. The insights derived from this analysis can assist financial institutions in making informed decisions regarding loan approvals and risk management.

## Dependencies
- Python
- Jupyter Notebook
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
