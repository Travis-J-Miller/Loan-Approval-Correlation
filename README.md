# Loan-Approval-Correlation
# Problem Statement
### _Business Problem_
"Dream Housing Finance company deals in all home loans. They have presence across all urban, semi urban and rural areas. Customer first apply for home loan after that company validates the customer eligibility for loan. Company wants to automate the loan eligibility process (real time) based on customer detail provided while filling online application form. These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History and others. To automate this process, they have given a problem to identify the customers segments, those are eligible for loan amount so that they can specifically target these customers."

### _Translate Business Problem into Data Science / Machine Learning problem_
This is a classification problem where we have to predict whether a loan will be approved or not. Specifically, it is a binary classification problem where we have to predict either one of the two classes given i.e. approved (Y) or not approved (N). Another way to frame the problem is to predict whether the loan will likely to default or not, if it is likely to default, then the loan would not be approved, and vice versa. The dependent variable or target variable is the Loan_Status, while the rest are independent variable or features. We need to develop a model using the features to predict the target variable.

# Hypothesis Generation
Hypothesis Generation is the process of listing out all the possible factors that can affect the outcome i.e. which of the features will have an impact on whether a loan will be approved or not. Some of the hypothesis are:

- Education - Applicants with higher education level i.e. graduate level should have higher chances of loan approval<br>
- Income: Applicants with higher income should have more chances of loan approval<br>
-  Loan amount: If the loan amount is less, the chances of loan approval should be high<br>
- Loan term: Loans with shorter time period should have higher chances of approval<br>
- Previous credit history: Applicants who have repayed their previous debts should have higher chances of loan approval<br>
- Monthly installment amount: If the monthly installment amount is low, the chances of loan approval should be high
And so on<br>

Some of the hypothesis seem intuitive while others may not. We will try to validate each of these hypothesis based on the dataset.<br>
