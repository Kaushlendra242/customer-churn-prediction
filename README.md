# 🧠 Customer Churn Prediction

Predicting customer churn using machine learning techniques to help businesses proactively retain valuable customers.

---

## ✅ Objective

The goal of this project is to build a classification model that predicts whether a customer will **churn (leave)** or **stay** with the business based on their behavior, account features, and service usage.

## 📦 Dataset

 - **Source**: [Kaggle Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
 - - **Features**:
   - Customer demographics (gender, senior citizen, etc.)
   - Service details (internet, phone, contract type, etc.)
   - Account info (monthly charges, tenure, total charges)

  - **Target**: `Churn` (Yes/No)
---

## 🔍 Approach
### 1. Exploratory Data Analysis (EDA)
- Checked for missing values, outliers, and feature distributions
- Visualized churn correlation with categorical features

### 2. Data Preprocessing
- Label encoding & one-hot encoding
- Feature scaling (standardization)
- Train-test split (80-20)

### 3. Model Building
- Applied:
  - Logistic Regression ✅
  - Random Forest Classifier 🌳
  - Evaluated using Accuracy, Precision, Recall, and Confusion Matrix
 
---

## 📊 Results

Model              | Accuracy |
|-------------------|----------|
| Logistic Regression | 80.24%     |
| Random Forest       | 79.00%     |

- **Insight**: Contract type, tenure, and monthly charges had strong influence on churn.
- **Impact**: Helps businesses target high-risk customers with retention offers.

---

## ⚙️ How to Run

### 📁 Clone the Repository


```bash
git clone https://github.com/Kaushlendra242/customer-churn-prediction.git
cd customer-churn-prediction


 



