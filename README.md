# Customer-Churn-Analysis-and-Prediction
This project is a machine learning-based customer churn analysis and prediction model. The primary goal is to analyze customer data, understand the factors that lead to churn, and build a predictive model to identify customers at risk of churning.

# Dataset Used
- <a href = "https://github.com/alisha2926/Customer-Churn-Analysis-and-Prediction/blob/main/Telco-Customer-Churn.csv"> Dataset </a>

# Libraries 
- Pandas: For data manipulation and analysis.
- NumPy: For numerical operations.
- Seaborn & Matplotlib: For data visualization.
- Scikit-learn: For machine learning model building and evaluation.
  
# Key Steps
- Exploratory Data Analysis (EDA)
The EDA phase focuses on understanding the data and its characteristics. Key steps include:
- Data Loading and Inspection: The project begins by loading the Telco-Customer-Churn.csv dataset and inspecting the first few rows to understand its structure.
- Missing Value Check: The dataset is checked for any missing values to ensure data quality.
- Descriptive Statistics: Descriptive statistics are generated for numerical columns like tenure and MonthlyCharges to understand their distribution and central tendencies.
- Target Variable Analysis: The distribution of the Churn variable is visualized to show the imbalance between customers who have churned (Yes) and those who have not (No). This is a crucial step for understanding the problem.
- Feature Analysis: The analysis also explores the relationship between various features and the Churn variable to identify potential drivers of churn.

# Model Building and Evaluation
A machine learning model is trained to predict customer churn. The process involves:

- Data Preprocessing: The categorical variables are handled, and the data is split into training and testing sets.

- Model Training: A Logistic Regression model is chosen and trained on the preprocessed data.

- Model Evaluation: The model's performance is evaluated using a confusion matrix. The confusion matrix helps to visualize the model's performance by showing the number of correct and incorrect predictions. It breaks down the predictions into four categories:
- True Positives (TP): Correctly predicted churned customers.
- False Positives (FP): Incorrectly predicted churned customers (Type I error).
- True Negatives (TN): Correctly predicted non-churned customers.
- False Negatives (FN): Incorrectly predicted non-churned customers (Type II error).

# Results
The confusion matrix provides a clear picture of the model's predictive capability, indicating its accuracy in identifying at-risk customers.
