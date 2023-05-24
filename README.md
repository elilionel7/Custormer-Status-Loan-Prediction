# Custormer-Status-Loan-Prediction (Course project from coursera)

This project involves the analysis and prediction of loan statuses, based on a dataset containing detailed information about customers whose loans are either paid off or defaulted.

The objective of this project is to develop a predictive model that can accurately determine if a loan will be paid off or go into collection.

#Dataset Overview
The dataset used for this project includes the following fields:

Loan_status: Indicates whether a loan is paid off or in collection.

Principal: The basic principal loan amount.

Terms: The origination terms of the loan, which can be weekly (7 days), biweekly, or a monthly payoff schedule.

Effective_date: The date when the loan originated and took effect.

Due_date: The due date for loan payment. Since it's a one-time payoff schedule, each loan has one single due date.

Age: The age of the loan applicant.

Education: The education level of the loan applicant.

Gender: The gender of the loan applicant.

#Modeling Approach
The project employs several machine learning algorithms to build the predictive models. These include Random Forest, Logistic Regression, K-Nearest Neighbor, and Support Vector Machine, all implemented using the Scikit-learn library.

#Model Evaluation
The models are evaluated based on their performance in predicting loan status on the test data. The performance metrics used are AUC score, Jaccard similarity coefficient, and F1-score. These metrics allow us to measure how well the models can predict the loan status, and help us compare and identify the most suitable model for this specific problem.

#Conclusion
This project represents an effort to leverage machine learning to improve decision-making in loan approval processes.  By accurately predicting loan statuses, financial institutions can optimize their loan collection efforts.




