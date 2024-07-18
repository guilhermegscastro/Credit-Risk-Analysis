# Credit Risk Analysis Project

## Overview
This project aims to predict loan default risk using machine learning techniques. The analysis is divided into fou main stages:
1. Data Preprocessing and Data Cleaning
2. Exploratory Data Analysis (EDA)
3. Logistic Regression Model Implementation
4. Random Forest Model Implementation

The project utilizes a dataset containing various features related to loan applications and borrower information.

## Notebooks

### 1. Credit Risk Analysis - 1.ipynb
This notebook lays the groundwork for the credit risk analysis. It involves:
- Loading the dataset (`credit_risk_dataset_feat.csv`).
  
 Data Import: <br/>
<img src="https://imgur.com/oZp9CZA.png" height="70%" width="90%" alt="Credit-Risk-Analysis"/>
<br />

- Cleaning the data and engineering features.
- Handle missing values (e.g., fill, drop).
- Conducting exploratory data analysis to gain insights into the data.

 Target Variable (loan status): <br/>
<img src="https://imgur.com/A6ByCtS.png" height="70%" width="70%" alt="Credit-Risk-Analysis"/>
<br />

### 2. Credit Risk Analysis - 2.ipynb
Exploratory Data Analysis (EDA) using Python involves examining and visualizing datasets to summarize their main characteristics, often with visual methods. Here are the key steps and components typically involved in EDA using Python:
- Visualize relationships (scatter plots, box plots, pair plots).
- Use bar charts, pie charts, and other categorical visualizations.

  Loan Grade (Distribution): <br/>
<img src="https://imgur.com/pR4MIHu.png" height="50%" width="50%" alt="Credit-Risk-Analysis"/>
<br />

- Correlation heatmaps to understand relationships between variables.

   Correlation (Heatmap): <br/>
<img src="https://imgur.com/LTPwCfJ.png" height="50%" width="50%" alt="Credit-Risk-Analysis"/>
<br />

   Loan Status vs Loan Percent Income (box plots): <br/>
<img src="https://imgur.com/W6Yr1UP.png" height="50%" width="50%" alt="Credit-Risk-Analysis"/>
<br />

- Normalize or scale numerical features.

   After Scaling (box plots): <br/>
<img src="https://imgur.com/YZXwBuV.png" height="50%" width="50%" alt="Credit-Risk-Analysis"/>
<br />
  
- Encode categorical variables (Dummy Variables).

### 3. Credit Risk Analysis - Logistic Regression.ipynb
This notebook focuses on building and evaluating a logistic regression model. Key steps include:
- Using the preprocessed data from the first notebook.
- Training a logistic regression model to predict loan defaults.
- Evaluating the model's performance using metrics such as accuracy, precision, recall, and ROC-AUC.
- Visualizing the results to interpret the model's performance.

   Logistic Regression (Confusion Matrix): <br/>
<img src="https://imgur.com/DAw2DM3.png" height="50%" width="50%" alt="Credit-Risk-Analysis"/>
<br />

   Logistic Regression (ROC curve): <br/>
<img src="https://imgur.com/1rTMahn.png" height="50%" width="50%" alt="Credit-Risk-Analysis"/>
<br />

   Logistic Regression (Default Probability Curve): <br/>
<img src="https://imgur.com/obY2SpI.png" height="50%" width="50%" alt="Credit-Risk-Analysis"/>
<br />

### 4. Credit Risk Analysis - Random Forest.ipynb
This notebook explores the use of a random forest model for predicting loan defaults. It covers:
- Using the preprocessed data from the first notebook.
- Training a random forest classifier.
- Evaluating the model's performance and comparing it with the logistic regression model.
- Visualizing feature importance to understand the impact of different features on the prediction.

   Random Forest (Confusion Matrix): <br/>
<img src="https://imgur.com/C2EZnZe.png" height="50%" width="50%" alt="Credit-Risk-Analysis"/>
<br />

   Random Forest (ROC curve): <br/>
<img src="https://imgur.com/XbbHZKn.png" height="50%" width="50%" alt="Credit-Risk-Analysis"/>
<br />

   Random Forest (Default Probability Curve): <br/>
<img src="https://imgur.com/1yaZ5VZ.png" height="50%" width="50%" alt="Credit-Risk-Analysis"/>
<br />

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
