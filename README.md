Data Analytics Portfolio Projects

This repository contains two Data Analytics and Machine Learning projects focused on solving real-world business problems using Python, data analysis, and predictive modelling.

Projects Included

1. Customer Lifetime Value (CLV) Prediction
2. HR Analytics – Employee Attrition Prediction

Both projects use synthetic datasets and demonstrate data preprocessing, exploratory data analysis, machine learning, model evaluation, and business insights.

---

Project 1: Customer Lifetime Value (CLV) Prediction

1. Business Problem

Businesses need to estimate how much value a customer may generate over the next 12 months. This helps organizations improve customer retention, loyalty programs, and marketing strategies.

2. Objective

To develop a machine learning regression model that predicts future customer lifetime value based on historical purchasing behaviour.

3. Dataset

The dataset contains 1,200 synthetic customer records with the following attributes:

- Frequency – Number of purchases.
- Recency Days – Days since the latest purchase.
- Average Order Value – Average purchase amount.
- Tenure Days – Duration of the customer relationship.
- Historical Monetary Value – Previous customer spending.
- Discount Rate – Discounts received.
- Returns Rate – Product return percentage.
- Future 12M CLV – Target variable.

4. Methodology

1. Load and inspect the dataset.
2. Check missing values and duplicate records.
3. Perform exploratory data analysis.
4. Select relevant customer behaviour variables.
5. Split the dataset into training and testing sets.
6. Compare Random Forest and Gradient Boosting regression models.
7. Evaluate models using MAE, RMSE, and R².
8. Predict customer lifetime value.
9. Classify customers into Low, Medium, and High Value segments.

5. Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Power BI

6. Expected Outputs

- Model performance metrics.
- Customer CLV predictions.
- Customer value segmentation.
- Data visualization charts.

7. Business Recommendations

- High-value customers: Provide loyalty benefits and personalized services.
- Medium-value customers: Introduce cross-selling and repeat-purchase campaigns.
- Low-value customers: Implement cost-effective customer engagement strategies.

8. Power BI Dashboard

Suggested dashboard components:

- Total customer count.
- Average predicted CLV.
- Customer distribution by CLV segment.
- Frequency versus predicted CLV.
- High-value customer analysis.

---

Project 2: HR Analytics – Employee Attrition Prediction

1. Business Problem

Employee turnover increases recruitment, onboarding, and productivity costs. Organizations need to understand the factors associated with employee resignations and identify employees who may need additional support.

2. Objective

To analyze employee data, identify factors associated with employee attrition, and develop a machine learning classification model to estimate attrition risk.

3. Dataset

The dataset contains 1,000 synthetic employee records with the following attributes:

- Age
- Department
- Monthly Income
- Distance from Home
- Years at Company
- Overtime
- Job Satisfaction
- Promotion Gap
- Work-Life Balance
- Attrition (Target Variable)

4. Methodology

1. Inspect data types and identify missing values and duplicates.
2. Analyze employee attrition patterns.
3. Perform exploratory data analysis.
4. Examine attrition by department, overtime, satisfaction, and income.
5. Encode categorical variables and scale numerical variables using a preprocessing pipeline.
6. Train a class-balanced Random Forest classification model.
7. Evaluate performance using accuracy, precision, recall, F1-score, and a confusion matrix.
8. Generate Low, Medium, and High attrition risk categories.
9. Identify important features using permutation importance.

5. Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Power BI

6. Expected Outputs

- Model performance metrics.
- Classification report.
- Confusion matrix.
- Feature importance visualization.
- Employee-level attrition risk scores.

7. HR Recommendations

- Review employee workload and overtime patterns.
- Conduct employee satisfaction and stay interviews.
- Improve career development and promotion opportunities.
- Review compensation using fair, role-based benchmarks.
- Encourage a healthy work-life balance.

8. Power BI Dashboard

Suggested dashboard components:

- Total employee count.
- Employee attrition rate.
- Department-wise attrition analysis.
- Overtime versus attrition.
- Job satisfaction analysis.
- Work-life balance analysis.
- Employee risk category distribution.

---

Installation and Execution

Install the required Python libraries:

pip install -r requirements.txt

Run Project 1 – CLV Prediction

python src/train_clv.py

Run Project 2 – Employee Attrition Prediction

python src/train_attrition.py

---

Project Outcomes

Through these two projects, the following practical skills are demonstrated:

- Data cleaning and preprocessing.
- Exploratory Data Analysis (EDA).
- Data visualization.
- Machine learning model development.
- Regression and classification.
- Model performance evaluation.
- Business insight generation.
- Predictive analytics.
- Power BI dashboard planning.

Disclaimer

These projects are developed for educational and portfolio demonstration purposes using synthetic datasets. The results are illustrative and should not be treated as verified business outcomes.

Employee attrition predictions should never be used as the sole basis for employment decisions.

---

Author: Vyshnavi Eedulakanti

Domain: Data Analytics | Machine Learning | Business Intelligence
