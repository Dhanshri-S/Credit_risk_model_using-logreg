# Credit_risk_model_using-logreg

The dataset has following variables:
person_age -	Age
person_income -	Annual Income
person_home_ownership -	Home ownership
person_emp_length -	Employment length (in years)
loan_intent -	Loan intent
loan_grade	- Loan grade
loan_amnt	 - Loan amount
loan_int_rate -	Interest rate
loan_status -	Loan status (0 is non default 1 is default)(target variable)
loan_percent_income	- Percent income
cb_person_default_on_file -	Historical default
cb_preson_cred_hist_length - Credit history length

We need to find out if the customer is eligible for loan.
As the target variable(loan_status) is binary we can use logistic regression here to find output.


After modelling we calculate metrics such as accuracy, precision, recall, f1 score etc and draw a roc curve to understand how good our model will perform.
