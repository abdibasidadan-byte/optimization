# optimization
Predictive Analysis of Customer Behavior in E-Commerce: Prediction of Average Order Value and Identification of High-Value Customers

Description:
This data analysis project explores customer behavior on an e-commerce platform using a dataset containing key metrics such as session duration, product detail views, app transactions, add-to-cart rate per session, discount rate per visited products, credit card info saving, average order value ("avg order value"), and a high-value customer indicator ("high_value_customer").
The code is structured in several steps:

Data Preparation: Loading from the clipboard, cleaning (replacing commas with periods for decimals), numeric conversion, and encoding of categorical variables (e.g., yes/no via LabelEncoder).
Regression Modeling: Use of an XGBoost model to predict average order value, with evaluation via RMSE and R² on a test set (30% of the data). Visualizations include a scatter plot of predictions vs. actual values, a correlation matrix, a boxplot of average basket by card saving, and a histogram of prediction errors.
Classification Modeling: Logistic regression with L2 regularization to identify high-value customers, based on selected features (session duration, product views, etc.). Evaluation via ROC-AUC score and ROC curve.

Data : https://github.com/Gayathri-Selvaganapathi/customer_churn_prediction/blob/main/data.csv
Acknowledgment to Gayathri-Selvaganapathi

