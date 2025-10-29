# Customer-Churn-Prediction-using-Machine-Learning
# 🧠 Customer Churn Prediction

This project predicts whether a customer will leave (churn) based on their profile and account activity.

---

## 📊 Project Overview
Customer churn is a major concern for companies. In this project, we use machine learning models like Logistic Regression, Random Forest, and XGBoost to predict customer churn.

---

## 📂 Dataset
- Dataset: `Churn_Modelling.csv`
- Features include: CreditScore, Age, Balance, Gender, Geography, etc.
- Target: `Exited` (1 = churned, 0 = retained)

---

## ⚙️ Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost

---

## 🚀 Steps Performed
1. Data loading and cleaning  
2. Feature encoding and scaling  
3. Model training (Logistic Regression, Random Forest, XGBoost)  
4. Evaluation using Accuracy, ROC Curve, and Confusion Matrix  

---

## 🏆 Best Model
**XGBoost Classifier** gave the highest accuracy (~87%).

---

## 📈 Results Visualization
Includes Confusion Matrix, ROC Curve, and Model Comparison Bar Graph.

---

## 🧾 How to Run
```bash
pip install -r requirements.txt
jupyter notebook churn_prediction.ipynb
