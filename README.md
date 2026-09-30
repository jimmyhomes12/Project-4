# Project-4

## Python Data Analytics Portfolio

This repository contains a complete Python data analytics and machine learning project focused on customer churn prediction for online retail.

## Included project

### Online Retail Customer Churn Prediction

**Location:** [`Python_Data_Analytics/Online_Retail_Churn_Prediction/`](Python_Data_Analytics/Online_Retail_Churn_Prediction/)

This project delivers an end-to-end workflow:
- data loading and cleaning
- feature engineering
- model training (Logistic Regression and Random Forest)
- evaluation with ROC metrics
- model explainability using feature importance and SHAP

## Repository structure

```text
Project-4/
├── README.md
├── online_retail_customer_data_extended.csv
└── Python_Data_Analytics/
    └── Online_Retail_Churn_Prediction/
        ├── data/
        │   ├── raw/online_retail_churn_raw.csv
        │   └── processed/online_retail_churn_clean.csv
        ├── models/
        ├── notebooks/
        ├── reports/
        ├── src/
        ├── requirements.txt
        └── README.md
```

## Quick start

1. Move to the project directory:
   ```bash
   cd Python_Data_Analytics/Online_Retail_Churn_Prediction
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run data preparation:
   ```bash
   python -m src.data_prep
   ```
4. Train models:
   ```bash
   python -m src.train_model
   ```
5. Generate evaluation plots and SHAP output:
   ```bash
   python -m src.evaluate
   ```

## Key outputs

- Trained model artifacts in `models/`
- Evaluation visuals in `reports/`
- Detailed analysis in `notebooks/01_online_retail_churn_analysis.ipynb`

For full project details, see the project README at:
[`Python_Data_Analytics/Online_Retail_Churn_Prediction/README.md`](Python_Data_Analytics/Online_Retail_Churn_Prediction/README.md)
