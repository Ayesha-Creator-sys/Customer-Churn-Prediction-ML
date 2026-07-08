Customer Churn Prediction using Machine Learning
Overview

This project predicts whether a telecom customer is likely to churn based on customer demographics, account information, and subscribed services. It applies machine learning techniques to preprocess the data, handle class imbalance, train multiple classification models, and evaluate their performance.

The goal is to help businesses identify customers who are at risk of leaving, enabling them to take proactive retention measures.

Features
Data preprocessing and cleaning
Exploratory Data Analysis (EDA)
Label Encoding for categorical variables
Handling class imbalance using SMOTE
Training multiple machine learning models
Model evaluation and comparison
Customer churn prediction
Saving and loading trained models using Pickle
Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
XGBoost
Imbalanced-learn (SMOTE)
Pickle
Machine Learning Models

The following models were trained and evaluated:

Decision Tree Classifier
Random Forest Classifier
XGBoost Classifier

After comparing the models, Random Forest was selected as the final model because it achieved the best performance.

Dataset

Dataset: Telco Customer Churn Dataset

The dataset contains customer information such as:

Gender
Senior Citizen
Partner
Dependents
Tenure
Phone Service
Internet Service
Contract Type
Payment Method
Monthly Charges
Total Charges

Target Variable:

Churn (Yes / No)
Project Workflow
Import required libraries
Load the dataset
Data cleaning and preprocessing
Exploratory Data Analysis (EDA)
Encode categorical features
Handle class imbalance using SMOTE
Split the dataset into training and testing sets
Train multiple machine learning models
Evaluate model performance
Save the trained model
Predict customer churn for new data
Installation

Clone the repository:

git clone https://github.com/your-username/Customer-Churn-Prediction-ML.git

Navigate to the project folder:

cd Customer-Churn-Prediction-ML

Install the required dependencies:

pip install -r requirements.txt

Run the project:

python customer_churn_prediction_using_ml.py
Project Structure
Customer-Churn-Prediction-ML/
│── customer_churn_prediction_using_ml.py
│── customer_churn_model.pkl
│── encoders.pkl
│── requirements.txt
│── README.md
│── LICENSE
│── .gitignore
Future Improvements
Develop a Streamlit web application
Hyperparameter tuning
Feature engineering
Model explainability using SHAP
Cloud deployment
Docker support
Author

Ayesha Saddiqa

MS Computer Science

Lecturer | Machine Learning Enthusiast

License

This project is licensed under the MIT License.
