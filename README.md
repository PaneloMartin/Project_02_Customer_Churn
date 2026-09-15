# 📊 Customer Churn Analysis & Prediction

## Project 02 – Data Analytics & Machine Learning Portfolio

![Python](https://img.shields.io/badge/Python-Data%20Analysis-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Manipulation-150458)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Analysis-4D77CF)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-F7931E)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Data%20Visualization-yellow)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Visualization-4C72B0)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626)
![Classification](https://img.shields.io/badge/ML-Classification-purple)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 📌 Project Overview

This project presents an end-to-end **Customer Churn Analysis and Machine Learning classification workflow** using customer data from a telecommunications company.

The objective was to identify the main factors associated with customer churn and develop predictive models capable of identifying customers with a higher risk of leaving the company.

The project combines:

- Data exploration
- Data cleaning and preprocessing
- Feature engineering
- Exploratory Data Analysis (EDA)
- Data visualization
- Machine Learning classification
- Model evaluation and comparison
- Feature importance analysis
- Business interpretation
- Customer retention insights

Rather than focusing only on predictive performance, the project connects Machine Learning results with **business-oriented customer retention decisions**.

---

## 🎯 Business Questions

The analysis was designed to answer several business questions:

- Which customers are more likely to churn?
- Which contract types present the highest churn risk?
- How does customer tenure affect churn?
- Are higher monthly charges associated with customer churn?
- Which internet services are associated with higher churn?
- Do Online Security and Tech Support influence customer retention?
- Are certain payment methods associated with lower churn?
- Which customer characteristics are the strongest churn indicators?
- Can Machine Learning models identify customers at risk of leaving?
- How can these findings support customer retention strategies?

---

## 🛠 Technologies & Skills

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook
- Data Cleaning
- Data Preprocessing
- Feature Engineering
- Exploratory Data Analysis
- Data Visualization
- Machine Learning
- Classification
- Logistic Regression
- Random Forest
- Model Evaluation
- Feature Importance
- Business Analysis
- Analytical Storytelling

---

## 📂 Dataset

The dataset contains customer information from a telecommunications company.

The available variables include information related to:

- Customer demographics
- Contract type
- Customer tenure
- Internet services
- Additional services
- Payment methods
- Monthly charges
- Customer account information
- Churn status

### Target Variable

The target variable used for the classification problem is:

**Churn**

- `Yes` → Customer left the company
- `No` → Customer remained with the company

The objective of the Machine Learning workflow is therefore to identify patterns associated with customers who are more likely to churn.

---

## 🔎 Exploratory Data Analysis

The Exploratory Data Analysis investigated the relationship between customer churn and several customer characteristics.

The analysis focused particularly on:

- Contract Type
- Customer Tenure
- Monthly Charges
- Internet Service
- Online Security
- Tech Support
- Payment Method
- Senior Citizen Status

The objective was not only to identify statistical patterns, but also to understand which customer characteristics could have practical implications for retention strategies.

---

## ⚙️ Machine Learning Pipeline

The project follows a complete Machine Learning workflow:

1. Data Cleaning
2. Data Preprocessing
3. Feature Engineering
4. Categorical Variable Encoding
5. Train/Test Split
6. Logistic Regression
7. Random Forest Classifier
8. Model Evaluation
9. Model Comparison
10. Feature Importance Analysis
11. Business Interpretation

This workflow transforms raw customer information into a structured classification problem and evaluates multiple models using consistent performance metrics.

---

## 🤖 Models

Two classification algorithms were implemented and compared.

### Logistic Regression

Logistic Regression was used as an interpretable baseline classification model.

Its advantages for this problem include:

- Simple interpretation
- Efficient training
- Probabilistic classification
- Strong baseline performance
- Useful benchmark for more complex models

### Random Forest

A Random Forest Classifier was also implemented to evaluate whether an ensemble model could improve predictive performance.

Its main characteristics include:

- Ability to capture non-linear relationships
- Interaction between multiple variables
- Robustness to complex feature relationships
- Feature importance estimation

---

## 📏 Model Evaluation

The models were evaluated using several classification metrics:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC AUC

| Model | Accuracy | Precision | Recall | F1 Score | ROC AUC |
|---|---:|---:|---:|---:|---:|
| Logistic Regression | **0.80** | **0.64** | **0.57** | **0.60** | **0.836** |
| Random Forest | 0.79 | 0.63 | 0.52 | 0.57 | 0.818 |

The results show that **Logistic Regression slightly outperformed Random Forest across the evaluated metrics**.

Despite being the simpler model, Logistic Regression achieved the highest ROC AUC at **0.836**, compared with **0.818** for Random Forest.

This demonstrates an important Machine Learning principle: **a more complex model does not necessarily produce better predictive performance**.

---

## 📈 Model Performance Comparison

The following visualization compares the main evaluation metrics for both classification models.

![Model Comparison](images/model_comparison.png)

Logistic Regression achieved slightly stronger overall performance, particularly in Recall, F1 Score, and ROC AUC.

For a churn prediction problem, Recall is particularly relevant because failing to identify customers who are actually at risk of leaving may result in missed retention opportunities.

---

## 📈 ROC Curve

The ROC Curve provides another perspective on the models' ability to distinguish between customers who churn and customers who remain.

![ROC Curve](images/roc_curve.png)

The Logistic Regression model achieved the highest ROC AUC:

**ROC AUC = 0.836**

This indicates a solid ability to discriminate between churn and non-churn customers.

---

## ⭐ Feature Importance

The Random Forest model was also used to explore the relative importance of different customer characteristics.

![Feature Importance](images/feature_importance.png)

Feature importance analysis helps connect predictive modeling with business interpretation by identifying which variables contribute most strongly to the model's decisions.

These results can help prioritize the customer characteristics that deserve greater attention when designing retention strategies.

---

## 💡 Key Business Insights

The analysis revealed several relevant patterns associated with customer churn.

### Contract Type

Customers with **month-to-month contracts** are significantly more likely to churn.

Longer-term contracts appear to be associated with stronger customer retention.

### Customer Tenure

Customers with **short tenure** present the highest churn risk.

This suggests that the early stages of the customer relationship may represent a critical retention period.

### Monthly Charges

Higher monthly charges are associated with increased churn.

Customers paying higher monthly amounts may therefore require additional attention from a retention perspective.

### Internet Service

Customers using **Fiber Optic services** show higher churn levels than customers using DSL.

This may indicate differences in pricing, expectations, service experience, or customer characteristics.

### Online Security

Customers without **Online Security** are considerably more likely to churn.

### Tech Support

Customers without **Tech Support** also show higher churn rates.

These additional services appear to be associated with stronger customer retention.

### Payment Method

Automatic payment methods are associated with lower churn.

This suggests that payment behavior may also provide useful information when identifying customers at risk.

### Senior Citizens

Senior citizens present higher churn rates than other customer groups.

This segment may therefore require differentiated retention strategies or customer support approaches.

---

## 🎯 Business Recommendations

Based on the analysis, several retention initiatives could be considered:

- Prioritize customers with **month-to-month contracts** for retention campaigns.
- Monitor customers during the **early stages of their tenure**.
- Investigate the relationship between **higher monthly charges and customer dissatisfaction**.
- Evaluate the customer experience associated with **Fiber Optic services**.
- Promote services such as **Online Security and Tech Support** where appropriate.
- Encourage convenient **automatic payment methods**.
- Develop targeted retention strategies for customer groups showing higher churn risk.
- Use predictive churn scores to prioritize customers for proactive retention actions.

The objective is not simply to predict churn, but to transform predictive results into **actionable business decisions**.

---

Project_02_Customer_Churn/

├── data/
├── images/
│   ├── feature_importance.png
│   ├── model_comparison.png
│   └── roc_curve.png
├── notebooks/
│   └── 02_customer_churn_analysis.ipynb
├── requirements.txt
├── README.md
└── .gitignore

---

## 🚀 Project Outcome

This project demonstrates the development of a complete **Machine Learning classification workflow**, from customer data exploration and preprocessing to predictive modeling, evaluation, and business interpretation.

The project demonstrates practical skills in:

- Python data analysis
- Data cleaning and preprocessing
- Feature engineering
- Exploratory Data Analysis
- Data visualization
- Classification modeling
- Logistic Regression
- Random Forest
- Model evaluation
- ROC AUC analysis
- Feature importance analysis
- Customer churn analysis
- Business insight generation
- Analytical storytelling

Most importantly, the project demonstrates the ability to connect **Machine Learning results with a real business problem: customer retention**.

As **Project 02** of the portfolio, it extends the exploratory analytics foundation developed in Project 01 by introducing predictive modeling and model evaluation.

---

## 👨‍💻 Author

**Martín Panelo**

**Data Analyst | Geophysicist | Scientific Computing**

Analytical professional combining data analytics, scientific computing, and geoscience experience, with a focus on Python, SQL, Power BI, data visualization, and business-oriented problem solving.

- GitHub: [PaneloMartin](https://github.com/PaneloMartin)
- LinkedIn: [Martín Panelo](https://www.linkedin.com/in/martinpanelo/)