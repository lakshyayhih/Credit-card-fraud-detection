💳 Credit Card Fraud Detection
🧠 Project Overview

This project focuses on detecting fraudulent credit card transactions using machine learning techniques.
The goal is to build a data pipeline that preprocesses raw transaction data, performs exploratory data analysis (EDA), and develops predictive models to classify transactions as fraudulent or non-fraudulent.

📊 Dataset

Source: Kaggle – Credit Card Fraud Detection Dataset

Data Link: Google Sheets Version

The dataset contains labeled transaction data with numerical and categorical features representing transaction amounts, times, and derived anonymized attributes.

⚙️ Project Workflow
1. Data Import & Cleaning

Imported labeled transaction data from Kaggle.

Cleaned and formatted data in Microsoft Excel to handle missing values, duplicates, and inconsistencies.

2. Exploratory Data Analysis (EDA)

Conducted EDA in Excel to understand data distribution and identify correlations between features and the target variable (fraudulent vs. non-fraudulent).

Visualized relationships and patterns to guide feature engineering.

3. Feature Engineering & Data Preparation

Used Python (Pandas, NumPy) for feature engineering and normalization.

Split the dataset into training and testing sets using scikit-learn.

4. Model Development

Implemented Linear Regression and other machine learning models using scikit-learn.

Trained and validated models to detect fraudulent transactions.

5. Model Evaluation

Evaluated performance using metrics such as R² Score and Mean Absolute Error (MAE).

Compared multiple models to identify the most effective approach for fraud detection.

🧰 Tools & Technologies

Python

Pandas, NumPy, scikit-learn

Microsoft Excel

Jupyter Notebook / VS Code

📈 Results & Insights

Achieved consistent model accuracy with improved data preprocessing and feature engineering.

Identified key features influencing fraud likelihood through correlation and EDA.

Compared models to select the most reliable one for deployment.

🚀 Future Scope

Integrate advanced algorithms such as Random Forest, XGBoost, and Neural Networks for better prediction accuracy.

Deploy the model using Flask or Streamlit for real-time fraud detection dashboards.

🧑‍💻 Author

Laxman Patel
Data Analyst | Machine Learning Enthusiast
LinkedIn
 • GitHub
