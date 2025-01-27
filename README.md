# Telecom Churn Prediction
## 📊 Project Overview
Customer churn is one of the critical metrics for businesses to monitor, as it directly impacts revenue. This project explores the factors contributing to churn in a telecom company and visualizes these patterns to provide data-driven recommendations.

## 📂 Dataset Description
- <a href="churn_dataset">Dataset</a>
- Size: 7,043 rows × 21 columns
- Attributes:
  - Customer demographics (e.g., gender, senior citizen status).
  - Services availed (e.g., internet service, phone service).
  - Account information (e.g., tenure, contract type, monthly charges).
  - Target variable: Churn (Yes/No).
 ## 🧹 Data Preprocessing
 1. Converted TotalCharges to numeric and handled missing values.
 2. Removed customerID as it does not influence churn.
 3. Transformed categorical variables into dummy variables for analysis.
## 🔍Exploratory Data Analysis
1. Correlation Heatmap: Highlights relationships between churn and other variables.
2. Gender Distribution: Shows the gender ratio of customers.
3. Senior Citizen Analysis: Visualizes the percentage of senior citizens.
4. Tenure Distribution: Displays the distribution of customer tenure.
5. Contract Type Impact: Analyzes churn rates based on contract types.
6. Dependents and Partners Analysis: Explores the relationship between dependents and partners.

## 📌Key Findings
1. Customers with month-to-month contracts have the highest churn rate.
2. Customers using fiber-optic internet are more likely to churn compared to DSL users.
3. Tenure is inversely proportional to churn; long-term customers are less likely to leave.
4. Electronic check payment methods are associated with higher churn rates.
## 📓Notebook
- <a href="source.ipynb">Notebook</a>
