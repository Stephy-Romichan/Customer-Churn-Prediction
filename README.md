
# 📉 Telecom Customer Churn Prediction

This project explores the prediction of customer churn in the telecom industry using machine learning models. It includes extensive preprocessing, dimensionality reduction with PCA, and model evaluation to understand how data transformation impacts predictive performance.

## 📊 Dataset Overview

- **Source**: Telecommunications company in California, Q2 2022  
- **Records**: 7,043 customers  
- **Target**: `Churn` – Binary label indicating whether a customer has churned or not

## 🎯 Project Objective

The goal is to assess how Principal Component Analysis (PCA) influences model accuracy and training time. The project involves:
- Data cleaning and preprocessing
- Feature transformation and scaling
- Handling imbalanced data via oversampling
- Model training and evaluation (with and without PCA)

## 📁 Project Structure

```text
telecom_customer_churn_prediction.ipynb
README.md
```

## 🛠 Techniques Used

- Missing value imputation
- Anomaly detection
- Normalization and scaling
- Principal Component Analysis (PCA)
- Oversampling using SMOTE
- Classification models (Logistic Regression, Random Forest, KNN, Naiye Bayes, Decision Tree and SVM)

## 📈 Results

Key takeaways:
- PCA enhanced performance in certain models by mitigating multicollinearity.
- Random Forest with PCA showed balanced precision and recall.
- Oversampling significantly improved prediction for the minority class.

## 🧪 Requirements

You can install the required dependencies via:

```bash
pip install pandas numpy scikit-learn imbalanced-learn matplotlib seaborn xgboost
```

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/telecom-customer-churn.git
   cd telecom-customer-churn
   ```
2. Launch the notebook:
   ```bash
   jupyter notebook telecom_customer_churn_prediction.ipynb
   ```

## 📌 Future Improvements

- Deploy model as a REST API
- Create an interactive dashboard for churn insights
- Experiment with deep learning models

## 🧑‍💻 Author

**Stephy Romichan**  
Master’s in Data Analytics Engineering | Passionate about data-driven decisions
