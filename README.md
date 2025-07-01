# Google Advanced Data Analystics Captsone Project 

Certificate of completion-https://www.coursera.org/account/accomplishments/professional-cert/5TTMZHDGUV8E
## Overview
The goal of this project was to create a predictive model for employee turnover through multiple logistic regression or through machine learning algorithms such as Decision Tree, Random Forest and eXtreme Gradient Boosting (XGBoost). This Google Advanced Data Analytics Professional Certificate capstone project utilized employee statistics from the fictional company Salifort Motors. The best model for this analysis was XGBoost with tuned hyperparameters. The metrics below are the metrics for the model's success on the test set:

| Model                | Precision | Recall   | F1       | Accuracy | AUC      |
|---------------------|-----------|----------|----------|----------|----------|
| XGBoost CV          | 0.973410  | 0.906898 | 0.938930 | 0.980429 | 0.981492 |
| Random Forest CV    | 0.950023  | 0.915614 | 0.932467 | 0.977983 | 0.980425 |
| Decision Tree CV    | 0.914552  | 0.916949 | 0.915707 | 0.971978 | 0.969819 |
| XGBoost (test)      | 0.976293  | 0.909639 | 0.941788 | 0.981321 | 0.952619 |
| Logistic Regression | 0.454082  | 0.178715 | 0.256484 | 0.827885 | 0.567957 |

Using an XGBoost (CV) model, we see that the main predictive features in determining if an employee will leave are: satisfaction_level, numbre_of_projects, tenure, last_evaluation , average_monthly_hours, work_accident, salary , department_sales.

##Business Understanding

Salifort’s senior leadership team is concerned about how many employees are leaving the company. The high turnover rate is costly in the financial sense because Salifort makes a big investment in recruiting, training, and upskilling its employees. If Salifort could predict whether an employee will leave the company, and discover the reasons behind their departure, they could better understand the problem and develop a solution.

## Data Understanding

The features included information on employee satisfaction, evaluation score, number of projects contributed to, average number of hours worked per month, tenure at the company, whether if they had a work accident, if they were promoted within the last 5 years, department worked for, and salary. The pie chart below shows the proportion of employees at Salifort Motors, with 0 meaning the employee has stayed and 1 meaning the employee has left.



![image](https://github.com/user-attachments/assets/214296a8-aaed-43a1-85ec-cb44434f0630)
