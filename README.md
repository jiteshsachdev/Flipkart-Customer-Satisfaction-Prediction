# Flipkart Customer Service Satisfaction Prediction

## 📌 Project Overview
This project aims to build an end-to-end machine learning classification model to predict customer satisfaction based on Flipkart’s customer service interaction data.

The goal is to help the business proactively identify dissatisfied customers and improve service quality, customer retention, and overall experience.

---

## 🎯 Business Objective
- Predict whether a customer is **Satisfied (1)** or **Dissatisfied (0)**
- Identify key drivers influencing customer satisfaction
- Enable data-driven decision making for customer support teams

---

## 🗂 Dataset Description
The dataset contains historical customer support interactions, including:
- Customer demographics
- Order details
- Issue categories and sub-categories
- Communication channels
- Customer feedback

---

## ⚙️ Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Google Colab

---

## 🔄 Project Workflow
1. Data Understanding
2. Data Cleaning & Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Encoding
5. Train-Test Split
6. Model Building
   - Logistic Regression
   - Random Forest
7. Model Evaluation
   - Confusion Matrix
   - Precision, Recall, F1-score
   - ROC-AUC
8. Feature Importance Analysis
9. Business Insights & Conclusion

---

## 📊 Model Performance

### Logistic Regression (Final Model)
- Accuracy: ~77%
- ROC-AUC: ~0.65
- Strong recall for satisfied customers

### Random Forest
- Lower overall performance
- Affected by class imbalance

**Final Model Selected:** Logistic Regression

---

## 🔍 Key Insights
- Return requests and order-related issues heavily influence dissatisfaction
- Fraud-related complaints are strong predictors of customer dissatisfaction
- Email channel interactions show notable impact on satisfaction
- Delayed and wrong deliveries significantly reduce satisfaction

---

## 🏁 Conclusion
The project successfully demonstrates how machine learning can be used to predict customer satisfaction and uncover actionable business insights. These insights can help Flipkart optimize customer service operations and improve customer retention.

---

## 🚀 Future Improvements
- Handle class imbalance using SMOTE
- Use advanced models like XGBoost
- Hyperparameter tuning
- Deploy model using Flask or Streamlit
