# credit-risk-classification
 train and evaluate a model based on loan risk.

The purpose of this analysis is to evaluate the performance of two logistic regression machine learning models in predicting the credit risk associated with loans. The analysis was conducted on financial data, specifically focusing on loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt. The objective was to predict the loan status, either as a healthy loan (0) or high-risk loan (1).

The stages of the machine learning process in this analysis included:

1. Splitting the data into training and testing datasets
2. Creating and fitting a logistic regression model with the original data
3. Evaluating the model's performance using accuracy, precision, and recall scores
4. Resampling the data using RandomOverSampler to address class imbalance
5. Creating and fitting another logistic regression model with the resampled data
6. Evaluating the performance of the resampled model using the same metrics

Methods used in this analysis include LogisticRegression and RandomOverSampler for resampling.