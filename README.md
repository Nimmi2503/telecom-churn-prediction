
# Telecom Churn Prediction

## Project Overview
This project aims to predict customer churn for a telecom company using customer behavior data from the first three months of the customer lifecycle. The model will help the company identify customers at risk of churning and suggest actions to retain them.

## Data Description
The dataset contains customer-level data for four months:
- **recharge**: Monthly recharge amount.
- **call usage**: Incoming and outgoing calls (`total_ic_mou`, `total_og_mou`).
- **internet usage**: 2G and 3G mobile internet usage (`vol_2g_mb`, `vol_3g_mb`).
- **Month**: The dataset contains data for months June, July, August, and September.

## Model Description
We used **Logistic Regression** (or **Random Forest**) to build a churn prediction model. The target variable is whether a customer churned in September based on their usage behavior in the previous months.

## How to Run the Code

### Dependencies
Install the required libraries:
```bash
pip install pandas numpy scikit-learn seaborn matplotlib
```

### Steps to Run
1. Clone this repository.
2. Run the Jupyter Notebook `churn_prediction.ipynb` to execute the analysis and model.
3. The notebook will provide insights on churn predictions and visualize the results.

## Model Evaluation
The model performance is evaluated using:
- **F1-score** for classification performance.
- **ROC-AUC** to measure the trade-off between true positive rate and false positive rate.
