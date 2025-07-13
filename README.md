# telecom-customer-churn-analysis
 Dataset
Source: Telco Customer Churn dataset (7,043 rows, 21–23 columns) 

Features include:

Demographics: Gender, SeniorCitizen, Partner, Dependents

Services: Phone, Internet, Streaming, Tech Support

Account Info: Tenure, Contract type, Payment method, MonthlyCharges, TotalCharges

Target: Churn – whether the customer left within the last month

🛠️ Project Workflow
Data Cleaning & Preprocessing

Removed duplicates and handled missing values

Converted data types (e.g., TotalCharges to numeric) 

Encoded categorical features and scaled numeric variables

Exploratory Data Analysis (EDA)

Visualized churn distribution and class imbalance

Analyzed relationships (e.g., churn vs. tenure, contract, monthly charges)

Discovered that high churn rates appear among short-tenure, month-to-month contracts 

Feature Engineering

Created derived features: e.g., AverageCharges, services count, tenure buckets

Optionally applied oversampling like SMOTE/ADASYN to address class imbalance 

Model Building & Evaluation

Split dataset into training/testing sets

Tested multiple classifiers: Logistic Regression, Random Forest, XGBoost, SVM, Gradient Boosting

Evaluated using accuracy, precision, recall, F1-score, ROC-AUC

Highlight: Gradient Boosting achieved highest F1 & ROC-AUC, indicating best balance of precision and recall 

Feature Importance & Business Insight

Identified top predictors (e.g., tenure, contract type, monthly charges, internet service)

Interpreted using feature importance plots or SHAP values (if implemented)

Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost.
