
# Bike Sharing Demand Prediction

This project aims to model the demand for shared bikes in the American market using multiple linear regression techniques. The analysis helps understand how various factors affect bike demand, which can assist in optimizing business strategies.

## Problem Statement

A US-based bike-sharing provider, BoomBikes, has faced significant revenue losses due to the COVID-19 pandemic. To recover, the company aims to better understand the factors influencing bike demand and prepare for post-pandemic market conditions. The goal is to identify significant variables that predict bike demand and use this information to adjust business strategies.

## Project Structure

- **Data Import and Understanding**: 
  - The notebook begins with importing the necessary data and libraries.
  - A detailed exploration of the dataset is conducted to understand the relationships between variables.
- **Data Preparation**: 
   - Checking for Missing Values and Inputing Them.
   - Checking the Correlation.
- **Modifying numerical variable as  Categorical variable as per the Data Dictionary for Data Visualization**:
   _ **Data Visualization using Categorical variables against count of total rental bikes**
   _** Dummy Variables Creation**:

##Splitting the Data into Training and Testing Sets

##Feature Scaling
  _**We will use MinMax scaling.**_

##Model Building:

- **Model Selection using RFE (Recursive Feature Elimination)**:
  - The notebook applies RFE to select the most significant features for predicting bike demand.

- **Model Evaluation**:
  - The selected model is evaluated using various metrics to ensure its reliability and accuracy.
  - Checking VIF
  - Removing the values based on High VIF & P value

## Residual Analysis of the train data

## Prediction using Test Data 
- **Making predictions on the test set**:

## **Plot for y_test VS y-test_pred**

### **_ VERIFYING R SQUARED VALUE FOR TRAIN AND TEST DATA_**
 - CALCULATE RSQUEARE FOR TEST DATA
## Requirements

##_SUMMARY_

### **_Regression Equation_**
 We can see that the equation of our best fitted line 


The following Python packages are required to run the notebook:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `sklearn`

You can install the necessary packages using:
 
pip install pandas numpy matplotlib seaborn scikit-learn
 

## How to Use

1. Clone the repository or download the notebook.
2. Install the required packages.
3. Open the notebook and run the cells sequentially.

## Data

The data used in this analysis is provided by the consulting firm hired by BoomBikes. It includes various features like weather conditions, seasonal factors, and other relevant metrics that influence the demand for bike-sharing services.

## Conclusion

The project provides a comprehensive approach to understanding the dynamics of bike-sharing demand. By analyzing the results, BoomBikes can optimize their strategies and improve their market presence post-pandemic.
