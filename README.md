# 🧠 Customer Churn Prediction

This project predicts whether a customer will **churn (leave the bank)** or **stay**, based on their demographic and account-related information.  
It applies **machine learning models** such as Logistic Regression, Random Forest, and XGBoost to identify customers likely to leave.

---

## 📊 Project Overview
Customer churn is one of the biggest challenges for subscription-based businesses.  
By predicting which customers are likely to leave, companies can take preventive measures and improve customer retention.  

This project uses real customer data from a bank to build predictive models and find the best-performing algorithm.

---

## 📂 Dataset
**Dataset name:** `Churn_Modelling.csv`  
**Source:** Kaggle  

| Column | Description |
|---------|-------------|
| CustomerId | Unique customer ID |
| CreditScore | Customer’s credit score |
| Geography | Country (France, Spain, Germany) |
| Gender | Male / Female |
| Age | Customer’s age |
| Tenure | Number of years with the bank |
| Balance | Account balance |
| NumOfProducts | Number of bank products used |
| HasCrCard | Credit card ownership (1 = Yes, 0 = No) |
| IsActiveMember | Active membership status (1 = Yes, 0 = No) |
| EstimatedSalary | Annual salary |
| Exited | Target variable (1 = Churned, 0 = Stayed) |

---

## ⚙️ Technologies Used
- **Python**
- **Pandas**, **NumPy** – Data analysis  
- **Matplotlib**, **Seaborn** – Data visualization  
- **Scikit-learn** – Model training & evaluation  
- **XGBoost** – Gradient boosting classifier  

---

## 🚀 Steps Performed
1. **Data Loading & Exploration**
2. **Handling categorical variables (Gender, Geography)**
3. **Feature scaling using StandardScaler**
4. **Model training:**
   - Logistic Regression  
   - Random Forest  
   - XGBoost  
5. **Evaluation metrics:**
   - Accuracy Score  
   - Confusion Matrix  
   - ROC Curve  
   - Classification Report  
6. **Model Comparison**

---

## 🏆 Results
| Model | Accuracy |
|--------|-----------|
| Logistic Regression | ~80% |
| Random Forest | ~86% |
| XGBoost | **~87% (Best Model)** |

✅ **XGBoost** achieved the best performance due to its ability to handle complex relationships and prevent overfitting.

---

## 📈 Visualizations
- 📊 Confusion Matrix  
- 📈 ROC Curve  
- 🔍 Model Accuracy Comparison Bar Chart
