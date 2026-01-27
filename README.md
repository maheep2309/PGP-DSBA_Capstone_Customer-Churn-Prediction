# PGP-DSBA_Capstone_Customer-Churn-Prediction
This capstone project builds a predictive churn model for AlphaCom using extensive data preprocessing, feature engineering, and multiple ML algorithms. It identifies churn drivers, evaluates models, and recommends strategies to reduce churn and improve customer retention.

# Capstone Project Summary
This project develops a complete end-to-end Customer Churn Prediction System for AlphaCom, aimed at identifying customers most likely to leave and uncovering the factors driving churn. The analysis begins with loading, validating, and preparing the dataset, ensuring accuracy through data-type conversions, duplication checks, missing-value treatment, and outlier handling. Extensive data preprocessing is conducted to clean inconsistencies, unify categorical labels, and engineer meaningful variables such as total charges, tenure groups, payment behaviour categories, and service usage indicators. These engineered features significantly improve model interpretability and performance. 

A thorough Exploratory Data Analysis (EDA) is performed to uncover behavioural patterns. Key findings show that churn is highest among month-to-month customers, users with electronic cheque payments, high monthly charges, lower tenure, and limited add-on services. Customers lacking fibre internet and premium support also churn more frequently. Visualizations highlight strong relationships between contract type, payment method, service mix, and churn, indicating structural weaknesses in AlphaCom’s retention strategy.

The modeling phase includes a wide range of algorithms—Logistic Regression, Naive Bayes, KNN, Random Forest, Decision Tree, XGBoost, SVM, Stacking, Bagging, and ANN. Prior to modeling, the dataset is scaled, encoded, and balanced using oversampling techniques to address churn imbalance.

Each model is evaluated using multiple metrics (Recall, Precision, F1-Score, ROC-AUC), with Recall prioritized to ensure the system captures as many churners as possible. Ensemble models, particularly XGBoost and Random Forest, consistently outperform baseline models due to their ability to capture nonlinear relationships, interactions, and complex customer behaviour patterns. Tuning and threshold optimization further enhance accuracy and generalization.

The best-performing model reveals the strongest churn predictors:
  - Month-to-month contracts
  - Online/electronic cheque payment modes
  - High monthly charges without proportional value additions
  - Low tenure and poor onboarding experience
  - Lack of bundled services (streaming, security, backup, multi-line services)
  - Inconsistent service quality or billing issues

Based on model findings, the project provides actionable recommendations:
  - Introduce loyalty benefits and pricing stability for month-to-month customers.
  - Optimize onboarding pathways for early-tenure subscribers.
  - Redesign billing communication and reduce friction in payment processes.
  - Promote bundled plans and value-added services to increase “stickiness”.
  - Use the predictive model to trigger proactive retention workflows such as targeted discounts, personalized offers, and customer-success interventions.

Overall, the project delivers a powerful, data-driven churn prediction engine that helps AlphaCom not only identify customers at risk but also understand the deeper drivers of dissatisfaction. This enables the company to shift from reactive to proactive customer retention, reducing revenue loss, improving customer experience, and strengthening long-term loyalty.
