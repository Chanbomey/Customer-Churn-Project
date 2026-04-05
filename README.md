# Customer-Churn-Project

Customer Churn Analysis & Prediction

Overview:

This project analyzes customer churn behavior and develop predictive models to identify customers at risk of leaving. The goal is to support decision-making and improve customer retention strategies.

Objectives:
- Identify key factors driving customer churn
- Build predictive models to classify churn risk
- Provide actionable business insights for retention

Data Preparation:
- Performed data cleaning and preprocessing
- Vonverted categorical variables into numerical format using one-hot encoding
- Split the dataset into training and testing sets to ensure proper model evaluation
- Applied random under-sampling to the training data to improve the model’s ability to detect churn customers

Exploratory Data Analysis
Analyzed churn distribution and customer characteristics
Identified relationships between tenure, usage, and churn
Detected multicollinearity among usage-related variables

🤖 Models Implemented
Decision Tree
K-Nearest Neighbors (KNN)
Multilayer (MLP)
Random Forest

📈 Model Evaluation
Models were evaluated using:
Precision
Recall
F1

Random Forest achieved the best performance and was selected as the final model.

🔍 Key Insights
Customers with low tenure are more likely to churn
Lower service engagement is associated with higher churn risk
Feature redundancy impacts certain models (e.g.,  KNN)

💡 Business Recommendations
Target early-stage customers with retention strategies
Improve onboarding and customer engagement
Monitor behavioral signals such as declining usage and complaints
Use predictive models to identify and prioritize high-risk customers

⚠️ Limitations
Limited exploration of advanced techniques such as cross-validation
Logistic Regression was not included for comparison
Model performance may vary with different data splits

🚀 Future Improvements
Implement cross-validation for more robust evaluation
Explore additional models (e.g., Logistic Regression, Gradient Boosting)
Optimize hyperparameters for improved performance

Tools:
