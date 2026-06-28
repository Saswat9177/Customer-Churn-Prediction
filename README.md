# 📊 Customer Churn Prediction using Machine Learning

## 📌 Overview

Customer churn is one of the biggest challenges faced by subscription-based businesses. Losing existing customers directly impacts revenue, and acquiring new customers is significantly more expensive than retaining current ones.

This project develops a **Customer Churn Prediction System** using Machine Learning to identify customers who are likely to leave a telecom service. By analyzing customer demographics, account information, and service usage, the system predicts churn and helps businesses take proactive measures to improve customer retention.

The project uses the **IBM Telco Customer Churn Dataset** and compares multiple machine learning algorithms to determine the most effective model for churn prediction.

---

## 🚀 Features

* Data preprocessing and cleaning
* Missing value handling
* Label Encoding of categorical variables
* Feature Scaling using StandardScaler
* Feature selection and analysis
* Training and evaluation of multiple ML models
* Customer churn probability prediction
* Identification of high-risk customers
* Data visualization and performance comparison
* Model serialization using Joblib

---

## 📂 Dataset

* **Dataset:** IBM Telco Customer Churn Dataset
* **Records:** 7,043 Customers
* **Features:** 21
* **Target Variable:** Churn (Yes/No)

---

## 🛠️ Technologies Used

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* XGBoost
* TensorFlow / Keras
* Joblib

---

## ⚙️ Machine Learning Models

The following models were trained and evaluated:

* Logistic Regression
* Random Forest Classifier
* Gradient Boosting Classifier
* XGBoost Classifier
* Artificial Neural Network (ANN)

---

## 📈 Model Performance

| Model               | Accuracy  | ROC-AUC   |
| ------------------- | --------- | --------- |
| Logistic Regression | **81.5%** | **0.861** |
| Random Forest       | 79.7%     | 0.837     |
| Gradient Boosting   | 80.6%     | 0.858     |
| XGBoost             | 79.4%     | 0.836     |
| Neural Network      | 81.3%     | 0.856     |

🏆 **Best Model:** Logistic Regression

---

## 📊 Visualizations

The project includes several visual analyses such as:

* Correlation Heatmap
* ROC Curves
* Model Comparison Graphs
* Feature Importance Analysis
* Customer Churn Distribution
* Churn Probability Distribution

---

## 📌 Workflow

1. Load Dataset
2. Data Cleaning
3. Data Preprocessing
4. Feature Engineering
5. Train-Test Split
6. Model Training
7. Model Evaluation
8. Model Comparison
9. Save Best Model
10. Predict Customer Churn

---

## 🎯 Key Findings

* Customer tenure is the most influential factor affecting churn.
* Customers with shorter tenure are more likely to leave.
* Higher monthly charges increase churn probability.
* Logistic Regression provided the best balance between accuracy and ROC-AUC.
* The system successfully identified high-risk customers using churn probability scores.

---

## 🔮 Future Improvements

* Deploy as a Flask or Streamlit web application.
* Integrate real-time prediction APIs.
* Use ensemble and deep learning techniques.
* Train on larger datasets for improved generalization.
* Develop an interactive dashboard for business analytics.

---

## 📁 Project Structure

```
Customer-Churn-Prediction/
│
├── Dataset/
├── Models/
├── Notebook/
├── Visualizations/
├── churn_prediction.py
├── requirements.txt
├── README.md
└── LICENSE
```

---

## 💡 Applications

* Telecom Industry
* Banking
* Insurance
* E-commerce
* SaaS Platforms
* Subscription-based Businesses

---

## 🤝 Team Members

* Saswat Mohapatra
* Somen Senapati
* Abhijit Sengupta
* Anurag Singh

---

## ⭐ Conclusion

This project demonstrates how machine learning can be effectively applied to predict customer churn and support business decision-making. By comparing multiple algorithms and analyzing customer behavior, the system provides actionable insights that can help organizations improve customer retention, reduce revenue loss, and build stronger long-term customer relationships.

If you found this project helpful, don't forget to ⭐ star the repository!
