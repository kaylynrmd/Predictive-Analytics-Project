# Predictive-Analytics-Project
# Predictive Analytics: Customer Churn Prediction

## Project Overview
This project applies predictive analytics techniques to predict customer churn using a telecom customer dataset.  
The objective is to identify customers at high risk of churn and extract insights that can inform retention strategies.

The project follows a full predictive analytics workflow:
- Data loading and exploration
- Preprocessing and feature engineering
- Baseline and advanced modeling
- Model evaluation and comparison
- Business insights and ethical considerations

---

## Dataset
- **Source:** Kaggle – Telco Customer Churn  
- **Observations:** ~7,000 customers  
- **Target Variable:** `Churn` (Yes / No)  
- **Features:** Customer demographics, service subscriptions, billing information, and contract details

---

## Repository Structure
Predictive-Analytics-Project/
- notebooks/ # Google Colab notebooks
- figures/ # Saved plots and visuals
- report/ # Final written report (PDF)
- README.md
- .gitignore

---

## Notebooks
Each notebook is hosted on Google Colab and linked below:

1. **Data Loading & Problem Definition**  
   `01_data_loading.ipynb`

2. **Exploratory Data Analysis (EDA)**  
   `02_eda.ipynb`

3. **Preprocessing & Feature Engineering**  
   `03_preprocessing.ipynb`

4. **Baseline Model – Logistic Regression**  
   `04_modeling_baseline.ipynb`

5. **Advanced Model – Random Forest**  
   `05_modeling_advanced.ipynb`

---

## Modeling Summary
- **Baseline Model:** Logistic Regression  
- **Advanced Model:** Random Forest (with hyperparameter tuning)
- **Evaluation Metric:** ROC-AUC (primary), precision, recall, confusion matrix

The Random Forest model outperformed the baseline model, achieving higher ROC-AUC and improved identification of churned customers.

---

## Key Business Insights
- Customers on month-to-month contracts have significantly higher churn rates.
- Short-tenure customers are at the highest risk of churn.
- Higher monthly charges are associated with increased churn likelihood.
- Targeted early-intervention strategies could significantly reduce churn.

---

## Ethical Considerations
- Predictions should be used to support customer retention and improve service, not penalize customers.
- Certain features may act as proxies for sensitive attributes, requiring fairness monitoring.
- Models should be retrained periodically to prevent performance degradation over time.

---

## Tools & Technologies
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Google Colab
- GitHub
- Chatgpt/Gemini

---

## Author
Kaylyn Dressel
