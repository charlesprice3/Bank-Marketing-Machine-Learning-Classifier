# 🧠 Term Deposit Subscription Classifier

This machine learning project builds and evaluates classification models to predict whether a customer will subscribe to a term deposit, based on their demographic and behavioral features.

## 📁 Project Overview

- **Goal**: Predict binary subscription outcomes using classification algorithms.
- **Dataset**: 45,000+ customer records from a bank marketing dataset.
- **Features**: 17 demographic and behavior-based input variables.
- **Target**: Subscription status (`yes` / `no`) for a term deposit.

## 🛠️ Methods & Workflow

1. **Data Preprocessing**
   - Cleaned and encoded categorical variables.
   - Handled missing values.
   - Performed exploratory data analysis (EDA).

2. **Modeling**
   - Implemented:
     - Decision Tree Classifier
     - Random Forest Classifier
   - Used **10-fold cross-validation** for robust model evaluation.

3. **Evaluation Metrics**
   - Precision, Recall, F1 Score
   - ROC-AUC Score
   - ROC Curve Visualization

## 📊 Results

Both classifiers were evaluated using a range of metrics. ROC curves were plotted to visualize the trade-off between true positive and false positive rates.

## 📓 Notebook

The main notebook is included in this repo:  
`bank_model_1.ipynb`

## 🔧 Dependencies

You can install the necessary Python packages using:

```bash
pip install -r requirements.txt
