# 2-churn-with-randomforest
"Predicting customer churn using Random Forest and Hyperparameter Tuning (GridSearchCV) to help businesses retain customers."
📊 Customer Churn Prediction using Random Forest
In this project, I developed a machine learning model to predict whether a customer will leave a telecommunications company (Churn). By identifying at-risk customers, businesses can take proactive measures to improve retention.

🚀 Key Features
Algorithm: Random Forest Classifier.

Optimization: Performed Hyperparameter tuning using GridSearchCV to find the best n_estimators (200 trees).

Data Preprocessing: Handled missing values in TotalCharges and converted categorical data using One-Hot Encoding.

📈 Business Insights (Based on Model Analysis)
According to the Feature Importance analysis (see chart below), the top factors driving customer churn are:

Total Charges & Monthly Charges: Financial burden is the strongest predictor of churn.

Tenure: New customers are much more likely to leave than long-term ones.

Contract Type: Customers with "Month-to-month" contracts have a significantly higher churn rate.

💡 Strategic Recommendations:
Retention Offers: Target customers with high monthly charges with "loyalty discounts".

Contract Conversion: Incentivize "Month-to-month" customers to switch to 1-year or 2-year contracts to increase stability.

Onboarding: Improve the experience for new customers (low tenure) to build early loyalty.

🛠️ Tech Stack
Python (Pandas, NumPy)

Scikit-Learn (RandomForest, GridSearchCV)

Matplotlib/Seaborn (Visualization)
