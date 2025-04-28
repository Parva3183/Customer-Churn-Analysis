-> 📈 Customer Churn Analysis for Telecom Company
This project focuses on analyzing customer churn behavior for a telecom company. The main goal is to identify key factors that influence churn and build a predictive model to help reduce churn rates and improve customer retention strategies.

-> 📂 Dataset Description
The dataset contains customer demographics, account information, and service usage details. Key features include:

Customer ID

Gender

Age

Tenure (months with the company)

Monthly Charges

Total Charges

Services Subscribed (Internet, Phone, Streaming, etc.)

Contract Type

Payment Method

Churn Status (Target variable)

-> ⚙️ Project Workflow
Data Collection: Loaded the telecom churn dataset.

Data Cleaning: Handled missing values, corrected data types, and removed duplicates.

Exploratory Data Analysis (EDA): Visualized churn distribution across demographics, service usage, and account details.

Feature Engineering: Created new features like tenure groups and total services subscribed. Encoded categorical variables.

Model Building: Built Logistic Regression, Random Forest, and XGBoost models to predict customer churn.

Model Evaluation: Evaluated models based on Accuracy, Precision, Recall, F1-Score, and ROC-AUC Curve.

Insights & Recommendations: Identified key churn drivers and proposed strategies to improve customer retention.

-> 🛠️ Technologies Used
Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

XGBoost

-> 📊 Key Insights
Customers with shorter tenure are more likely to churn.

Higher monthly charges correlate with a greater churn probability.

Customers subscribed to fewer services have higher churn rates.

Contract type and payment method significantly impact churn behavior.

-> 🚀 How to Run :-

1. Clone this repository:
git clone https://github.com/Parva3183/customer-churn-analysis.git

2. Install required libraries:
pip install -r requirements.txt

3. Open and run the Jupyter Notebook:
jupyter notebook


