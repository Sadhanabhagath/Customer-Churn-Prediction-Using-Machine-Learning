📊 Customer Churn Prediction Using Machine Learning (Logistic Regression)
Customer churn prediction is an important problem for businesses that rely on long-term customer relationships, such as telecom, banking, and subscription-based services. Losing customers can significantly impact revenue, so identifying customers who are likely to leave allows companies to take proactive measures to retain them.

This project focuses on predicting whether a customer will churn (leave the service) or remain with the company using Logistic Regression, a supervised machine learning algorithm used for binary classification problems.

The project uses the Telco Customer Churn dataset, which includes customer demographic information, service subscriptions, contract types, billing details, and usage patterns. The data is first preprocessed by handling missing values, encoding categorical variables, and performing exploratory data analysis (EDA) to understand patterns and relationships between features.

📌 Project Overview

Customer churn is one of the biggest challenges faced by telecom and subscription-based companies. Predicting customer churn helps businesses identify customers who are likely to stop using their services and take preventive measures to retain them.

This project uses Logistic Regression, a supervised machine learning algorithm, to predict whether a customer will churn or continue using the service.

🎯 Project Objectives

Predict customer churn using Logistic Regression

Perform data preprocessing and cleaning

Conduct Exploratory Data Analysis (EDA)

Train and evaluate a machine learning model

Visualize insights using graphs and charts

📂 Dataset

This project uses the Telco Customer Churn Dataset which contains customer information such as:

Customer demographics

Account information

Service subscriptions

Billing details

Contract type

Payment method

Customer tenure

Target Variable

Churn (Yes / No)
⚙️ Technologies Used
Technology	Purpose
Python	Programming language
Pandas	Data manipulation
NumPy	Numerical computation
Matplotlib	Data visualization
Seaborn	Statistical visualization
Scikit-learn	Machine learning modeling
🔍 Exploratory Data Analysis (EDA)

EDA helps understand patterns and relationships in the data.

Key analyses performed:

Churn distribution analysis

Contract type vs churn

Tenure vs churn

Monthly charges vs churn

Feature correlation heatmap

Example visualizations generated:

Churn distribution plot

Correlation heatmap

Confusion matrix

Feature importance chart

🤖 Machine Learning Model

This project uses Logistic Regression for binary classification.

Logistic regression predicts the probability of a customer churning using the following concept:

P(y=1|x) = \frac{1}{1 + e^{-(\beta_0 + \beta_1 x_1 + \beta_2 x_2 + ... + \beta_n x_n)}}

Where:
P(y=1∣x) = Probability of churn

x1,x2,..x1,x2... = Customer features

𝛽
β = Model coefficients

📈 Model Performance

Model evaluation metrics used:

Accuracy

Precision

Recall

F1 Score

Confusion Matrix

Example result:

Model	Accuracy
Logistic Regression	~80%
📊 Model Workflow
Data Collection
      ↓
Data Cleaning
      ↓
Exploratory Data Analysis
      ↓
Feature Encoding
      ↓
Train-Test Split
      ↓
Logistic Regression Model Training
      ↓
Model Evaluation
      ↓
Prediction
📁 Project Structure
Customer-Churn-Prediction
│
├── data/
├── notebooks/
├── src/
├── models/
├── images/
├── requirements.txt
├── README.md
└── LICENSE

Install dependencies:

pip install -r requirements.txt
▶️ Run the Project

Run the Python script:

python src/churn_analysis.py
🚀 Future Improvements

Compare multiple ML models (Random Forest, XGBoost)

Deploy model using Flask or Streamlit

Build an interactive dashboard

Use Deep Learning models

👩‍💻 Author

Bhagath Sadhana

Aspiring Data Analyst | Machine Learning Enthusiast

GitHub:
https://github.com/Sadhanabhagath/Customer-Churn-Prediction-Using-Machine-Learning.git

📜 License

This project is licensed under the MIT License.
