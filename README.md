# 🏨 Hotel Booking Cancellation Prediction

Predicting whether a hotel booking will be canceled, using historical booking data. This supervised machine learning project demonstrates classification techniques, model evaluation, and tuning to solve a real-world business problem.

---

## 🎯 Problem Statement

Hotel bookings often result in last-minute cancellations, hurting revenue and operational efficiency. This project aims to:

- Predict cancellations in advance
- Allow better inventory and staffing decisions
- Reduce revenue loss and optimize marketing efforts

---

## 📦 Dataset

The dataset contains hotel booking records including:

- Booking details (lead time, arrival date, room type, etc.)
- Customer data (country, previous cancellations, deposit type, etc.)
- Target variable: `is_canceled` (1 = Canceled, 0 = Not canceled)

---

## 🔧 Tools & Technologies

- **Language**: Python 🐍
- **Libraries**: pandas, numpy, matplotlib, seaborn, scikit-learn
- **Models Used**:
  - Logistic Regression
  - K-Nearest Neighbors (KNN)
  - Support Vector Machine (SVM)
  - Naive Bayes
- **Tuning**: GridSearchCV
- **Evaluation**: Accuracy, Precision, Recall, F1 Score, Confusion Matrix

---

## 📊 Workflow

### 1. Data Preprocessing
- Handled null values
- Feature engineering & one-hot encoding
- Outlier treatment & scaling

### 2. Exploratory Data Analysis (EDA)
- Cancellation trends across hotel types, months, and room categories
- Heatmaps & bar charts to identify key influencing features

### 3. Model Building & Evaluation
- Built baseline models
- Tuned KNN and SVM with GridSearchCV
- Compared performance using metrics

---

## ✅ Final Results

| Model              | Accuracy | Precision | Recall | F1 Score |
|-------------------|----------|-----------|--------|----------|
| Logistic Regression | 0.76     | 0.67      | 0.54   | 0.60     |
| KNN (Tuned)         | 0.81     | 0.72      | 0.66   | 0.69     |
| SVM (Tuned)         | 0.80     | 0.72      | 0.61   | 0.66     |
| Naive Bayes         | 0.41     | 0.35      | 0.97   | 0.51     |

### 🏆 Best Performing Model: **Tuned KNN**
- Balanced accuracy, precision, and recall
- Best generalization on test data

---

