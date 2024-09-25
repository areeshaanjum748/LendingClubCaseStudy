# Project Name: Lending Club Case Study

## Table of Contents
* [General Information](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
The project focuses on risk analytics within the banking and financial services domain. The primary business objective is to reduce the risk of financial losses by identifying key factors contributing to loan default. The analysis is based on a dataset from Lending Club, consisting of 39,717 records and 111 features, with the goal of improving loan approval decisions through exploratory data analysis (EDA).

### Problem Statement:
Loan defaults result in significant losses for lenders when borrowers fail to repay their loans. This project aims to minimize the risk of such defaults by identifying driving factors and highlighting risky applicants.

### Dataset Overview:
- Records: 39,717
- Features: 111
- Missing Values: Columns with over 50% missing data were removed.
- Key Features: Numerical and categorical columns were separated for a more effective analysis.

## Conclusions
Based on the analysis, the following factors are crucial in determining the likelihood of loan defaults:
1. **Grade**: Lower grades are associated with a higher probability of defaults.
2. **Purpose**: Loans for small businesses exhibit higher default rates.
3. **Address State**: Specific states (NV, AK, SD, FL) show higher default risks.
4. **Annual Income**: Borrowers with lower incomes are more likely to default.
5. **Interest Rate**: Default rates are higher for loans with interest rates above 13%.

## Technologies Used
- **Python**: Data cleaning, analysis, and visualization
- **Pandas**: Data manipulation
- **Matplotlib/Seaborn**: Data visualization
- **NumPy**: Numerical computation

## Acknowledgements
This project was inspired by the real-world problem of credit risk in the financial industry and is based on a dataset provided by Lending Club. 

## Contact
Created by [Apurv Aggarwal, @areeshaanjm748]. Feel free to reach out with any questions!
