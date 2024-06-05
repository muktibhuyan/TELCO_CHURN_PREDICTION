# TELCO_CHURN_PREDICTION - Case Summary
Telco, a leading telecommunications company, faces the challenge of customer churn, where a significant portion of its customer base discontinues services. To address this issue and enhance customer retention, Telco embarked on an **exploratory data analysis (EDA**) project, employing **logistic regression and random forest algorithms**. These advanced analytical techniques were utilized to gain insights into the factors influencing churn behavior. By analyzing various demographic, contractual, and service-related attributes, Telco aims to identify patterns and trends associated with churn. This project encompasses initial observations, interpretation of findings, and actionable recommendations derived from EDA and advanced machine learning models, providing Telco with valuable insights to devise effective retention strategies and bolster customer loyalty.


**Here's an overview of the steps taken during the EDA process:**

1.Data Understanding: • Comprehensive examination of the dataset to grasp its structure, variables, and overall content.
2.Data Preparation: • Rigorous data cleaning, formatting, and addressing of null values to ensure data quality and consistency.
3.Missing Values Imputation: • Imputation of missing values based on the type of data (categorical/numerical) to maintain data integrity.
4.Outlier Detection and Treatment: • Utilization of visualization tools such as box plots to identify outliers, followed by appropriate treatment to mitigate their impact on the analysis.
5.Univariate Analysis: • Examination of individual variables using various graphical representations: • Numerical data: Histograms, density plots. • Categorical data: Pie charts, Donut charts, Bar charts. • Temporal analysis: Line charts.
6.Bivariate Analysis and Correlation Assessment: • Exploration of relationships between pairs of variables, including correlation analysis to determine dependencies. • Visualization tools: Scatterplots, Heatmaps, Pair plots.
7.Multivariate Analysis: • Investigation into how demographic details influence customer response. • Visualization tools: Heatmaps, Bar charts.


**Initial Observations:**

1.Churn status indicates that approximately 26.5% of customers churned.
2.Most contracts (55%) are month-to-month, with 24.1% being two-year contracts and 20.9% being one-year contracts.
3.Around 70% of customers don't have online security, device protection, and online backup services.
4.The majority (78.3%) of customers use internet services.
5.Over 90% of customers use phone services.
6.Partner and multiple lines distributions are more evenly split between yes and no.
7.Electronic checks are the most popular payment method.
8.Approximately 59.2% of customers have opted for paperless billing.

**Interpretation after conducting EDA:**

1.Factors such as contract length, presence of additional services (online security, device protection, online backup), and certain demographic factors (dependents, partner) seem to influence churn rates significantly.
2.Longer contracts and the presence of additional services like device protection and online security are associated with lower churn rates.
3.Customers with higher monthly charges are more likely to churn.
4.The type of payment method used (especially electronic checks) and paperless billing also seem to impact churn rates.
5.Month-to-month contracts have a much higher churn rate compared to longer-term contracts, suggesting that longer contracts help in retaining customers.

**Recommendations based on observations:**

1.Encourage customers to opt for longer contract terms by offering incentives or discounts for signing longer contracts.
2.Promote additional services like online security, device protection, and online backup to customers, as these seem to correlate with lower churn rates.
3.Consider offering discounts or special offers to customers with high monthly charges to incentivize them to stay.
4.Encourage the use of payment methods other than electronic checks, as customers using electronic checks have the highest churn rates.
5.Provide options for paperless billing but also consider offering incentives or discounts for customers who opt for paper billing to reduce churn among paper bill recipients.
6.Focus retention efforts on customers with month-to-month contracts, as they have the highest churn rates. Consider offering incentives or promotions to encourage them to switch to longer-term contracts.
7.Monitor churn rates closely and continue to analyze customer behavior to identify additional factors that may influence churn and develop targeted strategies to reduce churn rates further.

**Logistic (Binomial) Regression and Random Forest Machine Learning algorithm  is used for Churn Model Prediction.**

**Logistic Regression Model Performance:** 
Accuracy: 1.0
Precision: 1.0
Recall: 1.0
F1 Score:  1.0

**Random Forest Model Performance:** 
Accuracy: 1.0
Precision: 1.0
Recall: 1.0
F1 Score: 1.0








