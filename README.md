# Data Description
- Attribute 1: person_age - Age
- Attribute 2: person_income - Annual Income
- Attribute 3: person_home_ownership - Home ownership
- Attribute 4: person_emp_length - Employment length (in years)
- Attribute 5: loan_intent - Loan intent
- Attribute 6: loan_grade - Loan grade
- Attribute 7: loan_amnt - Loan amount
- Attribute 8: loan_int_rate - Interest rate
- Attribute 9: loan_percent_income - Percent income
- Attribute 10: cb_person_default_on_file - Historical default
- Attribute 11: cb_person_cred_hist_length - Credit history length

# CONCLUDE
The signal risk model is built based on information about the client and related factors, such as
income, age, and others. In the problem of predicting possible signal risk, popular models include
Random Forest, Logistic Regression, Cecision Tree, XGBoost. Each model has its own
advantages and limitations, suitable for different situations. In which the XGBoost model
achieved the highest accuracy of 91% , followed by Random Forest with an accuracy of 90%
and Decision Tree with an accuracy of 0.87. Logistic Tegression had the lowest accuracy of
0.8055.
![image](https://github.com/royal317/Credit-Risk/assets/152999544/0d55e07d-eb31-43fd-a170-00166da00282)

Model development direction :
-- Incorporating more data sources: Credit risk models can benefit from additional data
sources beyond traditional financial data. Alternative data sources such as social media,
web search trends, and satellite imagery can provide additional insights into a borrower's
creditworthiness.
-- Exploring new modeling techniques: Advanced modeling techniques such as deep
learning, neural networks, and ensemble methods can improve the accuracy of credit risk
models. These techniques can handle non-linear relationships between variables and
capture more complex patterns in the data.
