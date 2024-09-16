# Loan Prediction Machine Learning Project 📊💡

Welcome to the Loan Prediction Machine Learning Project repository! This project focuses on predicting loan eligibility based on various customer attributes. By leveraging classification algorithms, we aim to develop a robust model that accurately assesses whether a customer qualifies for a loan.

## Overview 🌟

Our project encompasses the following key stages:

1. **Data Exploration:** We conducted an in-depth analysis of the dataset to understand the impact of attributes like marital status, education, and employment status on loan eligibility.

2. **Data Preprocessing:** We handled missing values, outliers, and encoded categorical variables to prepare the data for model training.

3. **Feature Analysis:** We explored trends and correlations in the data, uncovering insights into factors affecting loan approvals.

4. **Model Implementation:** We implemented and compared classification models, including Logistic Regression and K-Nearest Neighbors (KNN), to determine the best-performing algorithm for loan prediction.

5. **Performance Evaluation:** The models were evaluated using accuracy, precision, recall, and F1-score metrics. Logistic Regression emerged as the superior model with an accuracy of 79% compared to KNN's 77%.

6. **Predicting Loan Status:** We used the Logistic Regression model to predict loan status for new customers and analyzed the results to gain further insights.

## Key Features 🚀

- **Logistic Regression:** A powerful classification model that achieved an accuracy of 79%, effectively identifying eligible and ineligible loan applicants.
  
- **K-Nearest Neighbors (KNN):** An alternative classification model evaluated using GridSearchCV to find the optimal number of neighbors. Although KNN performed well, Logistic Regression proved to be more accurate.

- **Data Insights:** Analyzed patterns in the new customer data to identify trends such as the percentage of married individuals in semiurban areas who obtained loans.

- **Visualization:** Utilized visualizations to understand the distribution of loan status across different attributes like marital status and employment.

## Getting Started 🚀

1. **Clone the Repository:**
```bash
git clone https://github.com/yourusername/loan-prediction-project.git
```
2. **Navigate to the Project Directory:**
  ```bash
  cd loan-prediction-project
  ```
3. **Install Dependencies:**
  ```bash
  pip install -r requirements.txt
  ```
4. **Run Data Analysis and Model Training Scripts:**
   
To explore and preprocess the data:
```bash
jupyter notebook data_analysis.ipynb
```
To train and evaluate the models:
```bash
python train_models.py
```

## Performance Metrics 📈

- **Logistic Regression:**
  - **Accuracy:** 79%
  - **Precision:** 
    - Class 0: 0.95
    - Class 1: 0.76
  - **Recall:** 
    - Class 0: 0.40
    - Class 1: 0.99
  - **F1-score:** 
    - Class 0: 0.56
    - Class 1: 0.86

- **K-Nearest Neighbors (KNN):**
  - **Accuracy:** 77%
  - **Precision:** 
    - Class 0: 0.81
    - Class 1: 0.76
  - **Recall:** 
    - Class 0: 0.42
    - Class 1: 0.95
  - **F1-score:** 
    - Class 0: 0.55
    - Class 1: 0.84

## Insights and Analysis 🔍

- The Logistic Regression model demonstrates superior performance compared to K-Nearest Neighbors (KNN) with a higher accuracy of 79% versus 77%.
- Key insights from the new customer data reveal significant trends, such as the percentage of married individuals in semiurban areas who secured loans.
