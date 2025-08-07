# Hotel Booking Cancellation Prediction (Supervised Learning)

Predicting whether a hotel booking will be cancelled based on guest behavior and booking attributes using classification models.

---

## 💼 Project Overview

In the hotel industry, booking cancellations can cause massive disruptions in planning, revenue, and customer satisfaction. This project aims to solve that by building a machine learning model that predicts whether a given booking will be cancelled — **before it happens**.

This project was developed as part of a larger AI/ML learning journey and demonstrates my ability to perform end-to-end supervised learning workflows with real-world data.

---

## 📊 Problem Statement

**Objective:**  
Given historical data about hotel bookings, predict whether a booking will be cancelled.  

**Business Impact:**  
This prediction can help hotels:
- Proactively manage inventory and staffing
- Optimize overbooking strategies
- Improve customer communication and retention

---

## 🧠 Techniques & Tools Used

| Stage               | Techniques/Tools                                           |
|--------------------|------------------------------------------------------------|
| Data Analysis       | Pandas, NumPy, Seaborn, Matplotlib, Plotly                |
| Data Preprocessing  | Missing value handling, feature engineering, scaling      |
| Modeling            | Logistic Regression, KNN, Naive Bayes, SVM                |
| Model Evaluation    | Accuracy, Precision, Recall, F1-Score                     |
| Model Tuning        | Grid Search, Hyperparameter Tuning                        |
| Environment         | Python, Jupyter Notebook, Scikit-learn                    |

---

## 🔬 Key Steps

### 1. Exploratory Data Analysis (EDA)
- Visualized booking trends, guest patterns, and cancellation behaviors
- Identified class imbalance and regional trends

### 2. Data Preprocessing
- Handled missing values (documented rationale)
- Feature engineering on booking-related variables
- Scaled numeric features, stratified train-test split

### 3. Model Building
- Trained multiple classifiers (LogReg, KNN, Naive Bayes, SVM)
- Evaluated with confusion matrix, classification report, and F1 scores

### 4. Model Optimization
- Tuned hyperparameters using GridSearchCV
- Compared performance before and after tuning

### 5. Results & Recommendations
- Final model selected based on balanced performance
- Provided business recommendations for implementation

---

## 🧾 Project Outcomes

- **Best Model:** Support Vector Machine (after tuning)
- **Top Insights:**  
   - Longer lead times correlated with cancellations  
   - Certain distribution channels had higher cancellation rates  
   - Guests with no deposit and repeated bookings were more likely to cancel

---

## 🚀 How to Use This Project

```bash
pip install -r requirements.txt
jupyter notebook SL_Project_INN_Hotels_Project.ipynb
