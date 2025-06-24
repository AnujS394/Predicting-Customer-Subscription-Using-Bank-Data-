# 📊 Bank Marketing Analysis Using Machine Learning

A comprehensive machine learning project to analyze and predict customer behavior based on the Bank Marketing dataset. The notebook explores data patterns, performs feature engineering, and builds classification models to predict if a client will subscribe to a term deposit.

---

## 🔍 Overview

This project uses Python and machine learning libraries to:

- Understand customer behavior and marketing effectiveness
- Predict term deposit subscription outcomes
- Gain actionable business insights from campaign data

---

## 📁 Files in This Repository

| File Name                     | Description                                     |
|------------------------------|-------------------------------------------------|
| `bankmarketingdata (2).ipynb`| Jupyter notebook with code and analysis         |
| `README.md`                  | Project overview and instructions (this file)   |
| `bank-additional-full.csv`   | *(Optional)* CSV data from UCI repository       |

---

## 🧠 Features & Workflow

1. **Data Loading & Cleaning**
   - Import CSV file
   - Handle missing values and outliers

2. **Exploratory Data Analysis (EDA)**
   - Distribution plots
   - Correlation heatmaps
   - Class balance check

3. **Preprocessing**
   - Label encoding for categorical features
   - Feature selection & scaling

4. **Modeling**
   - Logistic Regression
   - Decision Tree Classifier
   - Random Forest Classifier

5. **Model Evaluation**
   - Accuracy, precision, recall, F1-score
   - Confusion matrix
   - Feature importance visualization

---

## ✅ Sample Output

- **Best Accuracy Achieved**: ~87% (Random Forest)
- **Top Features**: Contact type, month, previous outcome
- **Visual Insights**:
  - Customer age distribution
  - Subscription rate by job and education
  - Heatmaps showing feature correlation

---



## output image

![image](https://github.com/user-attachments/assets/57335636-1c56-4543-9f5c-6b4514704149)
![image](https://github.com/user-attachments/assets/e4dc8a0f-9925-4678-a276-4fe9ee1c4ce4)
![image](https://github.com/user-attachments/assets/e4d48753-2bb9-4d2d-8fe4-8477736674b2)
![image](https://github.com/user-attachments/assets/55c4b300-9cee-4276-b331-16eac0562dc6)
![image](https://github.com/user-attachments/assets/3cf90bea-788a-4b64-befa-f85d9889aa55)



## 📦 Dependencies

Make sure you have the following installed:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
