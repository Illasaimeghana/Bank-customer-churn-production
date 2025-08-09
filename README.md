# Bank-customer-churn-production


## 📌 Overview
This project predicts whether a customer is likely to leave (churn) from a bank using **Machine Learning** techniques.  
The goal is to help banks identify at-risk customers early and take proactive retention measures.

---

## 📊 Problem Statement
Customer churn is a critical issue in the banking sector, as acquiring new customers costs more than retaining existing ones.  
By predicting churn, banks can:
- Personalize offers
- Improve customer satisfaction
- Reduce customer attrition rate

---

## ⚙️ Technologies Used
- **Python 3**
- **Pandas**, **NumPy** – Data manipulation
- **Matplotlib**, **Seaborn** – Data visualization
- **Scikit-learn** – Machine Learning models
- **Jupyter Notebook / Google Colab** – Development environment

---

## 📂 Dataset
- **Source**: [Kaggle - Bank Customer Churn Dataset](https://www.kaggle.com/)
- **Features**:
  - Customer demographics (Age, Gender, Geography, etc.)
  - Account details (Balance, Credit Score, Tenure, Products)
  - Customer activity (Transactions, Card usage)
- **Target Variable**: `Exited`  
  - `1` → Customer churned  
  - `0` → Customer retained

---

## 🧠 Approach
1. **Data Preprocessing**
   - Handling missing values
   - Encoding categorical features
   - Scaling numerical data
2. **Exploratory Data Analysis (EDA)**
   - Understanding data trends & correlations
   - Visualizing churn patterns
3. **Model Building**
   - Logistic Regression
   - Random Forest Classifier
   - Gradient Boosting
4. **Model Evaluation**
   - Accuracy, Precision, Recall, F1-score
   - ROC Curve & AUC score
5. **Hyperparameter Tuning**
   - GridSearchCV for best performance

---

## 📈 Results
- **Best Model**: Random Forest Classifier
- **Accuracy**: ~86%
- **F1-Score**: 0.84
- Key factors influencing churn:
  - Low credit score
  - High balance but low activity
  - Short tenure in the bank


