# Telecom-Churn
Telecom Churn Case Study 

1. Introduction  
- Objective: Predicting customer churn to improve retention strategies  
- Business Impact: Helps businesses minimize revenue loss and increase customer loyalty  

2. Exploratory Data Analysis (EDA)  
- Missing Value Analysis: 11 records with missing Total Charges  
- Key Observations:  
  - Customers with monthly contracts are more likely to churn  
  - Higher monthly charges correlate with higher churn rates  
  - New customers have a higher churn probability  
- Multicollinearity Check: Variance Inflation Factor (VIF) used to detect correlated features  

3. Data Preprocessing  
- Handling missing values  
- Standardizing features for model consistency  

4. Model Development  
- Algorithms Used:  
  - K-Nearest Neighbors (KNN) for similarity-based classification  
  - Random Forest for robust decision-making  
- Feature Engineering: Selection of relevant predictors  

5. Model Evaluation  
- Performance assessment using k-Fold Cross-Validation  
- Metrics: Accuracy, Precision, Recall, F1-score  

6. Business Insights & Recommendations  
- High-risk customer identification: Focus retention efforts on new and high-monthly-charge customers  
- Improving customer engagement: Personalized offers for monthly contract users  
- Optimizing pricing strategies: Revising high-tier plans to reduce churn rates  
