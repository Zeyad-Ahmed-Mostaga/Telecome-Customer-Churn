# Telecome Churn Prediction Task 📊

## Project Overview
Customer churn is a significant issue for businesses, and predicting it accurately helps in taking proactive measures to retain customers. This project focuses on building a machine learning model to predict customer churn using various classification algorithms.

## Dataset
The dataset used for this project consists of customer-related attributes such as:
- Account length
- Voice mail plan
- Number of voicemail messages
- Total day, evening, night, and international minutes & calls
- Customer service calls
- Churn (Target Variable: 1 = Churn, 0 = No Churn)

### Data Sources
- **Train Data:** `churn-bigml-80.csv`
- **Test Data:** `churn-bigml-20.csv`

## Features and Methodology
The project follows a structured data science workflow:

### 1. Data Exploration & Preprocessing
- Handling missing and duplicate values
- Checking data types and updating them
- Dropping redundant features
- Encoding categorical variables
- Scaling numerical features
- Handling class imbalance using SMOTE

### 2. Exploratory Data Analysis (EDA)
- Distribution of numerical and categorical features
- Correlation analysis and feature selection
- Pivot tables to analyze churn across different features
- Data visualization using Matplotlib and Seaborn

### 3. Machine Learning Models
The following models were trained and evaluated:
- **Logistic Regression**
- **Naive Bayes**
- **K-Nearest Neighbors (KNN)**
- **Decision Tree Classifier**
- **Random Forest Classifier**
- **AdaBoost Classifier**
- **Gradient Boosting Classifier**
- **XGBoost Classifier** (used for feature importance analysis)

### 4. Model Evaluation
- Accuracy, Precision, Recall, and F1-Score were computed for each model.
- Confusion Matrices were visualized.
- Hyperparameter tuning was performed using GridSearchCV.
- Feature importance analysis was conducted.

## Results
- The **XGBoost model** demonstrated the best performance.
- The feature importance analysis showed that **customer service calls and total day minutes** are the most critical predictors of churn.
- Hyperparameter tuning significantly improved the performance of Random Forest and Gradient Boosting models.

## Installation & Usage
### Prerequisites
Ensure you have Python installed along with the following libraries:
```bash
pip install pandas numpy scikit-learn imbalanced-learn xgboost lightgbm matplotlib seaborn tqdm joblib pickle
```

### Running the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/churn-prediction.git
   cd churn-prediction
   ```
2. Run the Jupyter Notebook or Python script:
   ```bash
   python Churn Prediction Task.py
   ```

## Author
- **Name:** Zeyad Ahmed Mostafa  
- **Email:** ziada00700@gmail.com  
- **Phone:** +20 1200249877  
