#  Customer Churn Analysis with Tree-Based Models

This project analyzes customer churn behavior using machine learning models. We explore various supervised learning techniques to predict whether a customer will churn based on contract details, services, and account information.

##  Objective

To develop predictive models that classify customers as likely to churn or not, using:

- Decision Tree
- Random Forest
- AdaBoost
- Gradient Boosting

##  Key Features

- **EDA (Exploratory Data Analysis):** 
  - Tenure-based cohort analysis
  - Churn correlation heatmaps
  - Service and contract-based histograms

- **Predictive Modeling:**
  - Multiple tree-based classifiers compared
  - Accuracy, Precision, Recall, F1-score, and Confusion Matrix evaluated
  - Feature importance visualized for interpretability

## Tools & Technologies

- Python
- Jupyter Notebook
- Pandas, NumPy
- Seaborn & Matplotlib
- Scikit-learn

## Dataset

The dataset contains information about customers, their subscription plans, and whether they have churned. It includes variables like:

- `tenure`
- `MonthlyCharges`
- `Contract`, `PaymentMethod`
- `OnlineSecurity`, `TechSupport`, etc.

## Model Performance

| Model               | Accuracy | Recall (Yes) | F1-Score (Yes) |
|---------------------|----------|--------------|----------------|
| Decision Tree       | 0.78     | 0.47         | 0.54           |
| Random Forest       | 0.79     | 0.46         | 0.54           |
| AdaBoost            | 0.78     | 0.46         | 0.54           |

## Key Insight

Churn is **highly correlated** with shorter tenure, month-to-month contracts, and lack of security/tech support services.  
Longer-term customers are **less likely** to churn.

---

## Author

**Emmanuel Ikhimwin**  
Master of Artificial Intelligence | Western Sydney University  
[GitHub Profile](https://github.com/ikhimwinemmanuel)

---

## Note

This project is part of my learning journey to showcase my skills and build an AI-focused portfolio.