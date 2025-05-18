Customer Churn Analysis - Summary Report
________________________________________
1. Data Preprocessing
•	Loaded dataset: Customer Churn.csv.
•	Cleaned and transformed data:
o	Replaced blank values in the TotalCharges column with 0.
o	Converted TotalCharges to float datatype.
o	Mapped SeniorCitizen values: 0 to "No" and 1 to "Yes".
•	Confirmed there were no missing/null values in the dataset.
________________________________________
2. Exploratory Data Analysis (EDA)
Customer Churn Overview
•	Churn Count Plot: Visualizes the number of customers who churned versus those who did not.
•	Churn Percentage Pie Chart: Illustrates the proportion of churned customers.
Demographic Insights
•	Gender: No significant difference in churn rates between male and female customers.
•	Senior Citizens: A higher proportion of senior citizens have churned compared to non-seniors.
Usage & Contract Patterns
•	Tenure:
o	Customers with shorter tenure are more likely to churn.
o	Customers with longer tenure tend to remain.
•	Contract Type:
o	Monthly contracts are associated with higher churn rates.
o	Long-term contracts (yearly or more) show lower churn rates and better customer retention.
________________________________________
3. Key Insights
•	Higher churn rates are seen among:
o	Customers with monthly contracts.
o	Customers with shorter tenure.
o	Senior citizens.
•	Gender does not significantly affect churn behavior.
________________________________________
Conclusion: To reduce churn, companies should consider promoting long-term contracts, enhancing engagement early in the customer lifecycle, and providing targeted support to senior customers.

