# Kaggle-Bank-Lending-Prediction

Data Format:
The dataset consists of two files, lending_train.csv and lending_topredict.csv. The lending_train.csv file contains the training data, which you can use to train your classifier. The goal is to predict the loan repayment status for individuals listed in the lending_topredict.csv file. The data in both files is in comma-separated values (CSV) format.

Features:
The dataset includes the following features:

ID: Unique loan identifier.
requested_amnt: Amount requested by the borrower.
loan_duration: Length of the loan.
employment: Client's job title.
employment_length: Time spent on the current job.
race: Client's race.
reason_for_loan: Reason for the loan request.
extended_reason: Extended reason for the loan request.
annual_income: Client's annual income.
debt_to_income_ratio: Debt-to-income ratio.
employment_verified: Verification status of employment.
public_bankruptcies: Number of public bankruptcies.
zipcode: Anonymized zip code (last 3 digits).
state: State of residence.
home_ownership_status: Status of home ownership.
delinquency_last_2yrs: Debt delinquency in the last 2 years.
fico_score_range_low: Lowest FICO credit score.
fico_score_range_high: Highest FICO credit score.
fico_inquired_last_6mths: Whether FICO score was requested in the last 6 months (0=No, 1=Yes).
months_since_last_delinq: Months since the last debt delinquency.
revolving_balance: Revolving credit balance.
total_revolving_limit: Total revolving credit limit.
type_of_application: Type of loan application (Individual, Joint App).
any_tax_liens: Presence of any tax liens (0=No, 1=Yes).
loan_paid: Target variable indicating if the loan was paid (Paid=1 or Not paid=0). In the lending_topredict.csv file, this field contains a question mark "?".

Your goal is to develop a robust machine learning model using the training data that can accurately predict the loan repayment status for the borrowers in the lending_topredict.csv file. The evaluation metric for this competition will be based on the accuracy of your predictions.
