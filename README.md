- Problem Statement
The bank provides financial services/products such as savings accounts, current accounts, debit cards, etc. to its customers. In order to increase its overall revenue, the bank conducts various marketing campaigns for its financial products such as credit cards, term deposits, loans, etc. These campaigns are intended for the bank’s existing customers. However, the marketing campaigns need to be cost-efficient so that the bank not only increases their overall revenues but also the total profit. You need to apply your knowledge of EDA on the given dataset to analyse the patterns and provide inferences/solutions for the future marketing campaign.
Your target is to do end to end EDA on this bank telemarketing campaign data set to infer knowledge that where bank has to put more effort to improve it's positive response rate.

In This project first i import the libraries(pandas, numpy, matplotlit.pyplot, seabort).
Read the file and chek the first few rows of the dataframe.
start the data cleaning by Fixing the Rows and Columns.
-Delete summary rows: Total and Subtotal rows.
-Delete incorrect rows: Header row and footer row.
-Delete extra rows: Column number, indicators, Blank rows, Page No.
-Change the types of the column according to the needs.

Impute/Remove missing values

- Handling Outliers
Imputation
Deletion of outliers

 Standardising values- All same type valuse should be same unit.

- Univariate Analysis
Segment- 2, Categorical unordered univariate analysis
Unordered data do not have the notion of high-low, more-less etc. Example:
Type of loan taken by a person = home, personal, auto etc.
Organisation of a person = Sales, marketing, HR etc.
Job category of persone.
Marital status of any one.
Create Bar charts for Martiol status and jobs

-Categorical ordered univariate analysis.
Create Pi chart for education and response.


- Bivariate and Multivariate Analysis - (Numeric- numeric analysis)
Create scatter plot of balance and salary variabl.
Create scatter plot of balance and age.
Create the pair plot of salary, balance and age.
Create a Heatmap for the correlation matrix of salary, balance and age.

-Numerical categorical variable
Groupby the response to find the mean and median of the salary with response no & yes then plot the box plot of salary for yes & no responses.
Plot the box plot of balance for yes & no responses.

- Categorical categorical variable

Calculate the mean of response_flag with different education categories, Martial, Loan, Housing, age.

- Multivariate analysis
Create Heatmap of education vs marital vs response_flag
Create Heatmap of Job vs marital vs response
Create HeatmapEducation vs poutcome vs response

