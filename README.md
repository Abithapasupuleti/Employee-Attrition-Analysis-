Problem Statement: Employee attrition impacts productivity and morale, making it essential to understand its causes. This study analyzes objective factors like job satisfaction, work-life balance, and compensation to identify controllable and uncontrollable contributors to attrition. The goal is to create a model to predict employees at risk of leaving, allowing the company to implement strategies to improve retention.
Data: 
Research Questions: 1. What are the key indicators that signal an employee is likely to leave the company?
                    2. What is the probability of employee attrition given various contributing factors?
These questions aim to identify specific predictors of attrition and estimate the likelihood of an employee's departure based on those factors, helping to inform targeted retention strategies.
Tools & Libraries: Python (Scripting), CSV File (Data storage), Pandas (Data exploration and analysis), Seaborn, Matplot lib (Data Visualizations), Scikit learn (ML Models) & Jupyter Notebook (IDE).
Methods: 
1. Gathered the data and imported to a CSV file.
2. Read the CSV file and cleaned the data in pandas like removing null values, duplicates, outliers, handling categorical Variables etc.
3. Exploratory Data Analysis
4. Implemented Machine Learning models like Logistic Regression, Decision Tree Classifier, Random Forest Classier
5. ROC-AUC Ensemble Score for Employee Attrition Prediction
Evaluated the ensemble performance of three predictive models—Logistic Regression, Decision Tree, and Random Forest—using Receiver Operating Characteristic Area Under the Curve (ROC-AUC) analysis. The combined ROC-AUC score for this ensemble model is **0.80**, indicating a strong predictive capacity.
Methodology
- ROC-AUC was calculated individually for each model and combined for the ensemble.
- False Positive Rate (FPR) and True Positive Rate (TPR) were obtained by applying the `roc_curve` method on `y_test` and the ensemble's `final_prediction`.

The ROC curve below illustrates the model's ability to differentiate between employees likely to stay and those at risk of leaving.
<img width="304" alt="image" src="https://github.com/user-attachments/assets/0024124a-bade-40e1-a2fa-c24c60da1c71">



Outcome:







