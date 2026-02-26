Customer Churn & Revenue Analysis

Project Overview :
This project analyzes telecom customer data to predict customer churn and estimate revenue loss. Machine learning and SQL analysis are used to identify high-risk customers and provide business insights for customer retention.

Objectives :
* Analyze customer behavior using SQL queries.
* Predict customer churn using Machine Learning.
* Identify revenue at risk due to churn.
* Detect high-value customers likely to leave.

Dataset :
Source : IBM Telco Customer Churn Dataset
Dataset Link : https://raw.githubusercontent.com/IBM/telco-customer-churn-on-icp4d/master/data/Telco-Customer-Churn.csv

Technologies Used :
* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn
* SQLite (SQL queries)
* Random Forest Classifier

Project Workflow :
1. Data collection from dataset link
2. SQL-based analysis (churn rate, revenue at risk)
3. Data preprocessing and cleaning
4. Feature engineering (Customer Lifetime Value)
5. Model training using Random Forest
6. Model evaluation and feature importance analysis
7. Revenue leakage analysis

Project Architecture :
Dataset -> SQL Analysis -> Data Preprocessing -> Feature Engineering -> Random Forest Model -> Evaluation -> Business Insights

Machine Learning Model :
Algorithm : Random Forest Classifier
Accuracy : 79.8%
Evaluation Metrics :
  * Precision
  * Recall
  * F1 Score
  * Confusion Matrix

Key Results :
* Model predicts customer churn with 79.8% accuracy.
* Identifies important features affecting churn.
* Calculates revenue loss from churn customers.
* Detects high-value churn customers.
* Estimated total revenue at risk due to churn: $139,130.85.

Project Files :
'churn_analysis.ipynb' -> main project code
'processed_telco_churn.csv' -> processed dataset

Business Impact :
This project helps telecom companies identify customers likely to churn and reduce revenue loss through data-driven decision making.

Future Improvements :
* Hyperparameter tuning
* Deep learning models
* Model deployment using web application

Author :
Ishika Halder
