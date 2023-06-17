# Bank-Customer-Leads-Dashboard
## Loan Application Analysis

This project aims to analyze a dataset of loan applications and visualize the findings using Power BI.

## Data Cleaning

The dataset required some cleaning and preprocessing before visualization. The following steps were taken:

- Conversion of 'DOB' and 'Lead_Creation_Date' columns to datetime.
- Conversion of 'Monthly_Income', 'Loan_Period', 'Interest_Rate', 'Loan_Amount', 'Existing_EMI', and 'EMI' columns to float.
- Filling of NaN values in 'Loan_Period', 'Interest_Rate', 'Loan_Amount', 'Existing_EMI', and 'EMI' columns with 0.
- Mapping of 'Source_Category' to more recognizable sources ('A', 'B', 'C' to 'linkedin'; 'D', 'E', 'G' to 'google'; 'F' to 'facebook').
- Mapping of 'Primary_Bank_Type' values to more readable forms ('P' to 'Primary', 'G' to 'Govt').
- Replacing 'City_Category' values with 'Metro', 'Small Town', and 'Village'.
- Mapping 'Employer_Category1' to relevant sectors ('A' to 'Technology', 'B' to 'Consulting', 'C' to 'Finance').
- Dropping of the 'Customer_Existing_Primary_Bank_Code', 'City_Code', 'Employer_Code', 'Employer_Category2', and 'Source' columns.

All preprocessing was done using Python. The cleaned data was then ready for analysis and visualization in Power BI.

## Power BI Dashboard

The Power BI dashboard was created to visualize the key findings of the analysis. The dashboard includes:

- Two Donut Charts: These display the distribution of genders and employer categories within the dataset.
- Scatter Plot: This plot compares the total monthly income and total loan amount across source categories, separated by gender.
- Bar Chart: This displays the count of approved loans for each gender category.
- Filters: These allow the visualization to be filtered by quarter and month, providing more granular insight into the data.

The Power BI dashboard offers a clear and interactive way to understand the loan application data, and can be easily updated with new data for ongoing analysis.

Power BI Dashboard](Pdf/LeadsDashBoard.pdf)

