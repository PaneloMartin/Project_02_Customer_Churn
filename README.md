# 📊 Customer Churn Analysis & Prediction

An end-to-end Machine Learning project focused on analyzing customer churn and building predictive models to identify customers at risk of leaving a telecommunications company.

The project combines Exploratory Data Analysis (EDA), data preprocessing, feature engineering, predictive modeling, and business interpretation to generate actionable customer retention insights.

---

# 📈 Model Performance Comparison

![Model Comparison](images/model_comparison.png)

---

# ⭐ Top 10 Most Important Features

![Feature Importance](images/feature_importance.png)

---

# 📈 ROC Curve

![ROC Curve](images/roc_curve.png)

---

# 🎯 Project Objectives

The main goals of this project are:

- Perform a complete Exploratory Data Analysis (EDA).
- Identify the main factors influencing customer churn.
- Prepare the dataset for Machine Learning.
- Train and evaluate predictive classification models.
- Compare different Machine Learning algorithms.
- Translate model results into business insights.

---

# 📂 Dataset

The dataset contains customer information from a telecommunications company, including:

- Customer demographics
- Contract information
- Internet services
- Additional services
- Payment methods
- Monthly charges
- Customer tenure
- Churn status

### Target Variable

**Churn**

- Yes → Customer left
- No → Customer stayed

---

# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

# 📊 Exploratory Data Analysis

The EDA explored relationships between customer churn and several business variables, including:

- Contract type
- Customer tenure
- Monthly charges
- Internet service
- Online Security
- Tech Support
- Payment method
- Senior Citizen status

Multiple visualizations and business insights were generated for each feature.

---

# 🤖 Machine Learning Pipeline

The project follows a complete Machine Learning workflow:

1. Data Cleaning
2. Data Preprocessing
3. Feature Engineering
4. One-Hot Encoding
5. Train/Test Split
6. Logistic Regression (Baseline)
7. Random Forest Classifier
8. Model Evaluation
9. Feature Importance Analysis
10. Business Interpretation

---

# 📈 Models Compared

### Logistic Regression

- Baseline classification model
- Highly interpretable
- Excellent benchmark performance

### Random Forest

- Ensemble learning model
- Captures non-linear relationships
- Provides feature importance rankings

---

# 📏 Evaluation Metrics

| Model | Accuracy | Precision | Recall | F1 Score | ROC AUC |
|-------|----------|-----------|--------|----------|---------|
| Logistic Regression | 0.80 | 0.64 | 0.57 | 0.60 | 0.836 |
| Random Forest | 0.79 | 0.63 | 0.52 | 0.57 | 0.818 |

---

# 💡 Key Business Insights

The analysis revealed several important drivers of customer churn:

- Customers with month-to-month contracts are significantly more likely to churn.
- Short-tenure customers present the highest churn risk.
- Higher monthly charges are associated with increased churn.
- Fiber optic customers churn more frequently than DSL customers.
- Customers without Online Security and Tech Support are considerably more likely to leave.
- Automatic payment methods are associated with lower churn.
- Senior citizens present higher churn rates.

These findings can support customer retention strategies by identifying high-risk customer segments before they leave.

---

# 📁 Project Structure

```text
Project_02_Customer_Churn/

├── data/                      # Dataset
├── images/                    # Figures displayed in README
│   ├── feature_importance.png
│   ├── model_comparison.png
│   └── roc_curve.png
├── notebooks/
│   └── 02_customer_churn_analysis.ipynb
├── reports/
├── src/
├── requirements.txt
├── README.md
└── .gitignore
```

---

# 🚀 Future Improvements

Possible future enhancements include:

- Hyperparameter tuning with GridSearchCV
- SHAP Explainability
- Compare additional ML algorithms (XGBoost, LightGBM)
- Interactive Power BI Dashboard
- Deploy the model using Streamlit

---

# 👨‍💻 Author

## Martin Panelo

Geophysicist transitioning into Data Analytics and Machine Learning.

📍 Buenos Aires, Argentina

- 💼 LinkedIn: https://www.linkedin.com/in/martinpanelo/
- 💻 GitHub: https://github.com/PaneloMartin

---

⭐ If you found this project interesting, feel free to connect with me on LinkedIn.