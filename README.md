# Customer Churn Prediction Using Machine Learning

This project focuses on predicting customer churn using machine learning techniques. The workflow involves data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and performance evaluation using advanced metrics like the AUC-ROC curve. Additionally, the feature importance is visualized for better interpretability.

## Dataset
The dataset used in this project is the **Telco Customer Churn** dataset, sourced from Kaggle. It is provided by IBM and contains information about a telecommunications company's customers, including demographic details, account information, and service usage patterns. The dataset is ideal for churn prediction tasks as it includes a target variable (`Churn`) that indicates whether a customer has left the company.

Key Features:
- **CustomerID:** Unique identifier for each customer.
- **Demographics:** Gender, SeniorCitizen, Partner, and Dependents.
- **Account Information:** Tenure, Contract type, Paperless billing, Payment method, Monthly charges, and Total charges.
- **Service Usage:** Information about internet, phone, and other optional services subscribed to by the customer.

The dataset can be accessed from [Kaggle: Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn).

## Project Overview
This repository contains a Jupyter Notebook that:
- Performs Exploratory Data Analysis (EDA): Data cleaning, visualization, and insight generation.
- Implements Feature Engineering: Selection and transformation of key features.
- Trains Classification Models: Logistic Regression, XGB Classifier, Gradient Boosting Classifier and Random Forest Classifier.
- Evaluates Performance Metrics: Confusion Matrix, AUC-ROC curve.
- Visualizes Results: Feature importance and evaluation metrics.

## Installation
To run this project on your local machine:

1. Clone this repository:
   ```bash
   git clone https://github.com/username/repository-name.git
   ```

2. Navigate to the project directory:
   ```bash
   cd repository-name
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook customer-churn-prediction-using-ml.ipynb
   ```
2. Run each cell sequentially to process the data, train the model, and evaluate its performance.
3. Visualize the results directly within the notebook.

## Results
### Confusion Matrix
*![Confusion matrix](https://github.com/user-attachments/assets/315cf444-0287-4291-8df5-9cf8bbab4419)*

### ROC Curve
*![ROC Curve](https://github.com/user-attachments/assets/abc887d3-3d85-4e66-8910-6ccec51c1a46)*


### Feature Importance
*![Feature Importance ](https://github.com/user-attachments/assets/8ae92362-df50-428d-863d-2a7b898bf002)*
Monthly Charges and Total Charges drive the model's predictions the most.


## Acknowledgments
This project is inspired by the need to reduce customer churn and improve business decision-making using data-driven methods. Special thanks to IBM and Kaggle for providing the Telco Customer Churn dataset.
