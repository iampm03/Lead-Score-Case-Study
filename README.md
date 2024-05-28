# Lead-Score-Case-Study
# Lead Scoring Case Study - X Education

## Overview

This repository contains the code and resources for a lead scoring case study conducted for X Education, an online education company. The goal is to build a logistic regression model to predict lead conversion and assign lead scores, helping the sales team prioritize high-potential leads and improve conversion rates.

## Project Structure
  -The dataset used for the analysis.
  - Data cleaning and preparation.
  - Exploratory data analysis (EDA).
  - Feature scaling.
  - Building and evaluating the logistic regression model.
  - Assigning lead scores and final model evaluation.
-
## Data

The dataset consists of various attributes such as Lead Source, Total Time Spent on Website, Total Visits, Last Activity, etc., with the target variable being 'Converted' (1 if converted, 0 if not).

## Approach

1. **Data Import and Cleaning**
   - Import the dataset and handle missing values.
   - Remove irrelevant columns and address 'Select' levels in categorical variables.

2. **Exploratory Data Analysis (EDA)**
   - Identify significant attributes impacting lead conversion.
   - Analyze variables like Lead Source, Total Time Spent on Website, and Total Visits.

3. **Feature Scaling**
   - Scale the features to ensure uniformity and improve model performance.

4. **Model Building**
   - Use Recursive Feature Elimination (RFE) for feature selection.
   - Address multicollinearity using Variance Inflation Factor (VIF) analysis.
   - Build a logistic regression model to predict lead conversion.

5. **Lead Scoring**
   - Assign lead scores based on the model’s probabilities, ranging from 0 to 100.

6. **Model Evaluation**
   - Evaluate the model using metrics such as accuracy, precision, recall, and F1-score.

## Recommendations

During peak periods with additional intern support, X Education should:
- Prioritize high-probability leads.
- Implement targeted LinkedIn outreach.
- Utilize automation tools for efficient lead management.

