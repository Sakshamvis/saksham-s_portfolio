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
