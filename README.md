# Customer-Churn-Project

Customer Churn Analysis & Prediction Models

Overview:

This project analyzes customer churn behavior and develops multiple predictive models to identify customers at risk of leaving. Model performance is evaluated using precision, recall, and F1-score, with a focus on selecting a model that generalizes well to unseen data. The results support data-driven decision-making and enable more targeted and effective customer retention strategies.

Objectives:
- Identify key factors driving customer churn
- Build predictive models to classify churn risk
- Provide actionable business insights for retention

Tools:
- Programming Language: Python
- Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn
- Machine Learning Models: Decision Tree, K-Nearest Neighbors (KNN), Multilayer (MLP), Random Forest, 
- Data Processing: One-hot encoding, feature scaling, train-test split
- Imbalance Handling: Random Under Sampling
- Environment: Jupyter Notebook

Data Preparation:
- Performed data cleaning and preprocessing
- Converted categorical variables into numerical format using one-hot encoding
- Split the dataset into training and testing sets to ensure proper model evaluation
- Applied random under-sampling to the training data to improve the model’s ability to detect churn customers

Exploratory Data Analysis
- Analyzed churn distribution and customer characteristics
- Identified relationships between churn and other variable such as tenure, usage, and subscription
- Detected multicollinearity among usage-related variables

Model Evaluation
- Models were evaluated using precision, recall, and F1-score, with a focus on the churn class due to class imbalance.
- Random Forest achieved the best overall performance, providing a strong balance between recall and precision, and was selected as the final model.

Key Insights
- Customers with shorter tenure are more likely to churn, indicating higher risk among newly acquired customers.
- Lower service usage and engagement are associated with increased churn risk, suggesting that less active users are more likely to leave.
- Customers who are both new and less engaged represent the highest-risk segment, highlighting the importance of targeted early-stage retention strategies.

Business Recommendations
- Target early-stage customers with retention strategies
- Improve onboarding and customer engagement
- Monitor behavioral signals such as declining usage and complaints
- Use predictive models to identify and prioritize high-risk customers

Limitations
- Limited exploration of advanced techniques such as cross-validation
- Logistic Regression was not included for comparison
- Hyperparameter tuning was performed using the test set, which can make reported performance optimistic
