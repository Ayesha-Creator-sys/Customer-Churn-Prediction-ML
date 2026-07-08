# 🚀 Customer Churn Prediction using Machine Learning

Predict customer churn using Machine Learning algorithms to help businesses identify customers who are likely to discontinue their services.

---

## 📖 Overview

Customer retention is one of the biggest challenges for subscription-based businesses. This project builds a machine learning model that predicts whether a customer is likely to churn based on demographic information, account details, and subscribed services.

The project includes data preprocessing, exploratory data analysis, handling class imbalance with SMOTE, training multiple machine learning models, and selecting the best-performing model for prediction.

---

## ✨ Features

* 📊 Exploratory Data Analysis (EDA)
* 🧹 Data Cleaning & Preprocessing
* 🔄 Label Encoding for Categorical Features
* ⚖️ Handling Class Imbalance using SMOTE
* 🌳 Decision Tree Classifier
* 🌲 Random Forest Classifier
* ⚡ XGBoost Classifier
* 📈 Model Performance Evaluation
* 💾 Save & Load Trained Model using Pickle
* 🔮 Predict Customer Churn for New Customers

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost
* Imbalanced-learn (SMOTE)
* Pickle

---

## 📂 Dataset

**Dataset:** Telco Customer Churn Dataset

### Features

* Gender
* Senior Citizen
* Partner
* Dependents
* Tenure
* Phone Service
* Multiple Lines
* Internet Service
* Online Security
* Online Backup
* Device Protection
* Tech Support
* Streaming TV
* Streaming Movies
* Contract
* Paperless Billing
* Payment Method
* Monthly Charges
* Total Charges

**Target Variable**

* Churn (Yes / No)

---

## 🤖 Machine Learning Models

The following models were trained and compared:

* Decision Tree Classifier
* Random Forest Classifier
* XGBoost Classifier

After evaluating all models, the **Random Forest Classifier** was selected as the final model due to its superior performance.

---

## 📁 Project Structure

```text
Customer-Churn-Prediction-ML/
│
├── customer_churn_prediction_using_ml.py
├── customer_churn_model.pkl
├── encoders.pkl
├── requirements.txt
├── README.md
├── LICENSE
├── .gitignore
└── dataset/
    └── WA_Fn-UseC_-Telco-Customer-Churn.csv
```

---

## ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/AyeshaSaddiqa/Customer-Churn-Prediction-ML.git
```

### Navigate to the Project Directory

```bash
cd Customer-Churn-Prediction-ML
```

### Install Required Packages

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

```bash
python customer_churn_prediction_using_ml.py
```

---

## 📊 Project Workflow

1. Import Libraries
2. Load Dataset
3. Data Cleaning
4. Exploratory Data Analysis
5. Feature Encoding
6. Handle Class Imbalance using SMOTE
7. Train-Test Split
8. Model Training
9. Model Evaluation
10. Save the Trained Model
11. Predict Customer Churn

---

## 📈 Model Evaluation

The models were evaluated using:

* Accuracy Score
* Confusion Matrix
* Classification Report
* Cross Validation

The **Random Forest** model achieved the best overall performance and was selected for final predictions.

---

## 🔮 Future Improvements

* Develop a Streamlit Web Application
* Hyperparameter Optimization
* Feature Engineering
* SHAP Model Explainability
* Docker Deployment
* Cloud Deployment (AWS, Azure, or Google Cloud)
* REST API using Flask or FastAPI

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repository, improve the project, and submit a pull request.

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 👩‍💻 Author

**Ayesha Saddiqa**

**MS Computer Science**

Lecturer | Machine Learning & AI Enthusiast

---

⭐ If you found this project helpful, consider giving it a **Star** on GitHub!

