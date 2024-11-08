**Problem Statement:** Employee attrition impacts productivity and morale, making it essential to understand its causes. This study analyzes objective factors like job satisfaction, work-life balance, and compensation to identify controllable and uncontrollable contributors to attrition. The goal is to create a model to predict employees at risk of leaving, allowing the company to implement strategies to improve retention.


**Data:** The dataset consists of 1,470 entries and 35 columns, with 11 categorical and 24 numerical variables. It contains no NULL values or outliers. The target variable, 'attrition', is binary, with values 'YES' or 'NO'.


**Research Questions:** 
                        
                        1. What are the key indicators that signal an employee is likely to leave the company?

                        2. What is the probability of employee attrition given various contributing factors?
These questions aim to identify specific predictors of attrition and estimate the likelihood of an employee's departure based on those factors, helping to inform targeted retention strategies.


**Tools & Libraries:** Python (Scripting), CSV File (Data storage), Pandas (Data exploration and analysis), Seaborn, Matplot lib (Data Visualizations), Scikit learn (ML Models) & Jupyter Notebook (IDE).


**Methods:**
1. Data Collection and Import: Gathered the dataset and saved it as a CSV file, loaded the CSV file into a pandas DataFrame.
      
2. Exploratory Data Analysis (EDA): Conducted EDA to identify patterns, trends, and key features for model development.
   
3. Model Implementation
Built and evaluated three machine learning models:
Logistic Regression
Decision Tree Classifier
Random Forest Classifier

4. ROC-AUC Ensemble Score for Employee Attrition Prediction: Assessed the combined performance of the three models using Receiver Operating Characteristic Area Under the Curve (ROC-AUC) analysis.The ensemble model achieved a ROC-AUC score of 0.80, indicating strong predictive capability.
Methodology: Calculated ROC-AUC for each model and combined the results to form the ensemble score.

5. Extracted the False Positive Rate (FPR) and True Positive Rate (TPR) by applying the roc_curve method on y_test and the ensemble’s final_prediction.
 
6. Model Robustness Testing: Performed a validity check to test the robustness of the model using k-fold cross-validation.


**Outcome:** This project identified key factors influencing employee attrition. While overtime and job level are commonly considered, attributes like job involvement and marital status also play a significant role. These factors are more modifiable by companies, offering opportunities to improve retention.








