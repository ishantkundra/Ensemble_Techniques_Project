# 📦 Ensemble Techniques Project – Telecom Churn Prediction & Automated ML Pipeline

## 📌 Project Overview

This project includes **two major components** focused on real-world telecom and IT use cases using advanced machine learning techniques. It highlights data merging, cleaning, feature engineering, model building with XGBoost, and automation of end-to-end workflows using modular Python functions.

---

## 📱 Part A: Telecom Customer Churn Prediction

### 🌐 Domain: Telecom Industry

### 📊 Datasets:
- `TelcomCustomer-Churn_1.csv`
- `TelcomCustomer-Churn_2.csv`

These datasets include demographic, service-related, and billing information for telecom customers, including whether they have churned or not.

### 🧩 Objective:
Build a classification model that predicts customer churn and help the company identify high-risk users for proactive retention.

### 🛠️ Key Steps:
- Merged data on `customerID` and validated completeness
- Handled missing values and type conversions for numerical columns
- Encoded categorical variables using the most appropriate techniques
- Standardized numerical features
- Split data into train/test sets (80:20)
- Trained and tuned an **XGBoost classifier**
- Evaluated the model using classification metrics on both train and test sets

### 📌 Outcome:
A fine-tuned XGBoost model with improved accuracy and recall, ready for deployment in a real-time churn prediction system.

---

## 🤖 Part B: Automated Machine Learning Pipeline

### 🖥️ Domain: IT / Automation

### 🧩 Objective:
Develop a fully automated ML workflow that accepts a CSV file, processes it, trains multiple classifiers, and saves the **best-performing model** as a `.pkl` file.

### 🛠️ Key Features:
- Modular pipeline with reusable functions:
  - Missing value handler
  - Data normalization
  - Encoding strategy
  - Model training and evaluation
- Trains multiple models (e.g., Logistic Regression, KNN, Decision Tree, Random Forest, XGBoost, AdaBoost)
- Evaluates all and selects the best based on validation accuracy
- Saves the final model using Python’s `pickle` module
- Designed with scalability and maintainability in mind

### 📌 Outcome:
A plug-and-play ML system that reduces manual effort in building workflows, aligns with industry practices, and can be extended for different datasets and use cases.

---

## ⚙️ Tools, Libraries & Skills Used

- **Languages & Libraries:** Python, Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn, Pickle
- **ML Techniques:** Logistic Regression, Decision Trees, Random Forest, K-Nearest Neighbors (KNN), XGBoost, AdaBoost
- **EDA:** Heatmaps, pairplots, distribution analysis, missing value treatment
- **Modeling:** Classification models, Hyperparameter tuning, Evaluation metrics
- **Other Skills:** Data cleaning, Encoding, Normalization, Modular ML workflow development

---

## 📁 Repository Structure

<pre>

.
├── code/
│   └── Final-IK.ipynb                             # Complete project notebook (Parts A & B)
│
├── dataset/
│   ├── TelcomCustomer-Churn_1.csv                # Customer churn base data (part 1)
│   └── TelcomCustomer-Churn_2.csv                # Customer churn additional data (part 2)
│
├── Problem Statement/
│   └── EST_Problem Statement document.pdf        # Project brief
│
├── .gitignore
└── README.md                                     # This file

</pre>

---

## 💡 Key Learnings

- Practical use of ensemble learning techniques like XGBoost and AdaBoost  
- Designing end-to-end ML systems using modular and scalable code  
- Automating data preprocessing and model evaluation  
- Data-driven insights to improve customer retention strategies  
- Building industry-style ML workflows with model persistence

---

## ✍️ Author

**Ishant Kundra**  
📧 [ishantkundra9@gmail.com](mailto:ishantkundra9@gmail.com)  
🎓 Master’s in Computer Science | AIML Track
