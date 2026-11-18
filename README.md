# Credit-Risk-Analysis-

## Table of Contents
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results and Findings](#results-and-findings)
- [Recommendations](#recommendations)
- [Limitations](#limitations)
- [References](#references)

### Project Overview

This project focuses on analysing borrower credit risk and identifying factors associated with loan defaults using Microsoft Power BI. The objective is to evaluate borrower characteristics, financial circumstances and loan attributes to identify patterns that may indicate a higher likelihood of default.
An interactive Credit Risk Analysis Dashboard was developed to help financial institutions, credit analysts and management understand default patterns, assess lending risks and support better credit approval and portfolio management decisions.
The analysis focuses on default rates across borrower age groups, income categories, homeownership status, loan burden categories and length of employment.

### Data Sources

The project uses the loan application and credit risk dataset obtained from Kaggle.

The dataset contains the following borrower and loan information:

* Loan amount.
* Loan grade.
* Loan intent.
* Borrower income.
* Homeownership status.
* Borrower age.
* Employment length.
* Loan interest rate.
* Loan-to-income ratio.
* Historical default status.

### Tools

The following tools and technologies were used for the project:

* CSV/Excel: Dataset storage, inspection and initial data assessment
* DAX for Creation of calculated columns, default rate measures and analytical indicators.
* Power Query for data extraction, transformation and cleaning.
* Microsoft Power BI for dashboard development, data modelling and visualisation.

### Data Cleaning and Preparation

Data preparation was carried out using Power Query in Power BI using the following steps:

1. Imported the credit risk dataset into Power BI.
2. Examined the dataset structure and reviewed the available columns.
3. Checked for missing values and duplicate records.
4. Identified and addressed missing values in relevant fields.
5. Reviewed numerical columns and corrected data types.
6. Standardised categorical variables for consistency.
7. Converted loan grade classifications into a consistent format (Grade A–Grade G).
8. Standardised loan intent descriptions, including Home Improvement and Debt Consolidation.
9. Reviewed borrower age and employment length categories.
10. Created additional calculated fields and classifications to support credit risk analysis.
11. Validated the loan default indicator to distinguish defaulted loans from non-defaulted loans.

### Exploratory Data Analysis 

Exploratory Data Analysis was carried out to understand the characteristics of borrowers and identify patterns associated with loan defaults. The main areas of focus are as follows:

* Distribution of borrowers across income categories.
* Borrower age distribution.
* Homeownership status.
* Employment length.
* Loan burden categories.
* Loan grades and loan purposes.
* Distribution of defaulted and non-defaulted loans.
* Relationship between borrower financial circumstances and default rates.

### Data Analysis

DAX measures and calculated columns were developed to support the analysis. The major areas of focus are as follows:

- Default Rate by Homeownership: Examines differences in default patterns across homeownership categories, including Rent, Own, Mortgage and Other.

- Default Rate by Age Range: Evaluates default rates across borrower age groups to identify age segments with relatively higher credit risk.

- Default by Income Category: This compares default rates across borrower income categories to assess how income levels relate to loan repayment risk.

- Default Rate by Loan Burden Category: Examines default rates across different loan burden classifications to understand the relationship between borrowers’ financial obligations and default risk.

- Default Rate by Length of Employment: This evaluates how employment history relates to loan default rates, helping identify whether borrowers with shorter employment histories demonstrate different risk patterns.

- Loan Status by Income of Borrower: Compares loan outcomes across income categories to understand the distribution of loan approvals and default status among different borrower segments.

Interactive slicers were created for Loan Intent and Loan Grade. These filters allow users to examine credit risk patterns for specific loan purposes and credit quality categories.

### Results and Findings

The results of the analysis are summarised as follows:

- The default rate by age range chart shows a significant difference in default risk across borrower age groups. The highest displayed rate is approximately 0.71 (71%), compared with approximately 0.27 (27%) for the lowest displayed age-group rate.
- Borrowers in the lowest income category recorded the highest displayed default rate, approximately 0.62 (62%), indicating a potential relationship between lower income levels and increased loan repayment risk.
- The middle-income category recorded a default rate of approximately 0.44 (44%), while the upper-middle-income and high-income categories recorded considerably lower rates of approximately 0.20 (20%) and 0.16 (16%), respectively.
- The default rate by homeownership analysis reveals differences across Rent, Own, Mortgage and Other categories, suggesting that homeownership status is a useful variable for borrower segmentation and credit risk assessment.
- The loan burden analysis shows variations in default risk across Very High, High, Moderate and Low loan burden categories. Borrowers with higher loan burdens warrant closer assessment because of their potential exposure to repayment difficulties.
- The employment length analysis indicates that default rates vary across employment categories, with the chart showing higher default risk among some shorter or less established employment groups than among longer-tenured groups.
- The loan status by borrower income chart reveals differences in loan outcomes across income categories, highlighting the importance of considering borrower income when assessing lending decisions.
- The interactive dashboard allows users to examine how default patterns change when filtering by loan intent and loan grade, supporting more focused credit portfolio analysis.

### Recommendations

The following recommendations are proposed based on the analysis:

- Additional attention should be given to borrowers in lower-income categories when evaluating affordability and repayment capacity.
- Risk-based lending criteria which Considers borrower age, income, employment history, homeownership and existing financial obligations should be introduced when assessing credit applications.
- The borrowers with high debt obligations should be reviewed to assess whether additional lending could create repayment difficulties.
- The disposable income and debt-to-income capacity should also be assessed rather than relying solely on gross income.
- The employment history and income consistency should be considered as part of the credit assessment process.
- Regularly monitoring of default rates across borrower segments to identify emerging credit risks.
- A risk-based pricing and lending limits should be considered while ensuring that lending decisions remain fair and compliant with applicable regulations.

### Limitations

The following limitations were observed:

* The analysis is based on historical loan and borrower information and may not reflect future repayment behaviour.
* The dashboard figures depend on the selected loan intent and loan grade filters.
* The analysis identifies associations between borrower characteristics and default rates but does not establish causation.
* Income, age, employment and homeownership alone are insufficient to determine an individual’s creditworthiness.
* The dataset may not capture changes in borrower circumstances after loan approval.
* External economic factors such as inflation, unemployment and interest rate changes may influence repayment performance but are not fully incorporated into the analysis.
* The dashboard is an analytical and decision-support tool, not an automated loan approval or rejection system.
* Further statistical testing and predictive modelling would be required to establish the predictive value of individual risk factors.

### References

* Credit Risk Analysis Dataset.
* Microsoft Learn – Power BI documentation.
* Microsoft Learn – Power Query documentation.
* Microsoft Learn – DAX (Data Analysis Expressions) reference.
* Microsoft Learn – Power BI data modelling and visualisation documentation.

   
