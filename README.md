# Loan Prediction Model 
#### About the dataset
This dataset, sourced from Kaggle's loan prediction challenge, contains structured data from the financial domain, focusing on loan applicants. It includes both numerical and categorical features such as income, education, employment status, credit history, and loan status, making it ideal for data analysis and machine learning. The data is likely collected automatically from loan application records, reflecting real-world financial processes. I chose this dataset to explore the key factors influencing loan approval decisions. I am analyzing these features to identify patterns and trends that influence loan approval status and to develop a predictive model to better understand the factors that lead to loan acceptance or rejection.

## Data Dictionary
- Columns:
  - Loan_ID: Unique identifier for each loan application  
  - Gender: Male or Female  
  - Married: Marital status of the applicant  
  - ApplicantIncome: Monthly income of the applicant  
  - CoapplicantIncome: Income of any co-applicant  
  - LoanAmount: Loan amount applied for  
  - Loan_Status: Loan approved (Y/N)
  - Loan_Amount_Term: The term of the loan (months)
  - Credit history – If the applicant has a credit history (1=Yes, 0 =No)
  - Dependent- Number of dependents the applicant has (0,1,2,3+)
  - Education- Education level (Graduate/Not Graduate)
  - Self_employed- Whether the applicant is self-employed (Yes/No)
  - Property_Area: are where property is located (Urban/Semiurban/Rural)
 
    
Note: Only Gender, Married, Dependents, ApplicantIncome, and LoanAmount were used for insights, while others were ignored. 

## Project Overview
1. **Exploratory Data Analysis (EDA):**
   - Visualized the distribution of categorical and numerical variables.
   - Analyzed relationships between loan status and key variables like applicant income, education level, and self-employed status.
   
2. Data Cleaning:
   - Handled missing values, particularly for Self_Employed and LoanAmount.
   - Checked for any outliers or inconsistencies in the data.
   
3. Visualizations:
   - Count plots for categorical variables (e.g., gender vs. loan status).
   - Box plots for numeric variables (e.g., applicant income vs. loan status).
   - Other visualizations include heatmaps, histograms, etc.

## Key Insights
- Higher incomes tend to have higher loan approval rates.
- Most loan approvals are associated with applicants having credit histories.
- Married applicants and applicants with dependents showed different approval rates.
- Self-employed applicants had varying approval chances.

## Tools and Libraries Used
- Programming Language: Python
-  Libraries: 
  - pandas for data manipulation
  - matplotlib and seaborn for visualizations
  - numpy for numerical operations

   You can access the dataset here: 
  
   
   Source: Kaggle Loan Prediction (train) https://www.kaggle.com/datasets/altruistdelhite04/loan-prediction-problem-dataset



