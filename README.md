# Employee-Retention-Analysis-Logistic-Regression
This project analyzes employee data to identify key drivers of attrition and builds a logistic regression model to predict whether an employee will leave or stay.
### Objectives
Perform exploratory data analysis to identify variables that significantly impact employee retention.
Visualize the relationship between salary level and retention.
Analyze the correlation between department and employee retention.
Build a logistic regression model using selected significant features.
Evaluate model performance using accuracy and confusion matrix.
### Exploratory Data Analysis (EDA)
Key findings from the analysis:
Salary level shows a clear trend — employees with lower salaries are more likely to leave.
Department influences retention, with certain departments like Hr experiencing higher turnover.
#### Bar charts were used to visualize:
Salary vs Retention
Department vs Retention
### Model
A Logistic Regression model was built using selected significant features.
Categorical variables were encoded using pd.get_dummies(), and the data was split using an 80/20 train-test split.
### Results
Model Accuracy: ~83–84%
Strong performance in predicting employees who stay
Lower recall for employees who leave due to class imbalance
### Tools
Python | Pandas | Matplotlib | Scikit-learn | Jupyter Notebook
