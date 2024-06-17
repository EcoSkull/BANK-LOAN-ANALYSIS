# Bank Loan Analysis 

## Project Overview

This project delves into a detailed analysis of bank loan data, utilizing SQL for data querying and manipulation, followed by visualization and further analysis in Power BI, Excel, and Tableau. The primary goal is to uncover insights related to loan applications, funding, repayments, and borrower demographics. The analysis spans various dimensions, including temporal (month, term), geographical (state), and categorical aspects (purpose, home ownership).

---

## Objectives

- Provide a holistic view of the bank's loan portfolio performance.
- Identify trends and patterns in loan applications, approval rates, and repayment statuses.
- Assess financial health through KPIs such as Total Funded Amount, Average Interest Rate, and Loan Status.
- Facilitate strategic decision-making for the bank's credit and loan offerings.
  
---

## Data Source

The project is based on a comprehensive [dataset](https://github.com/EcoSkull/BANK-LOAN-ANALYSIS/blob/main/financial_loan.csv) stored in SQL Server, encompassing various aspects of bank loans, including loan amounts, issue dates, interest rates, DTI ratios, and loan statuses.

---

## Methodology

1. **Data Ingestion and Database Creation**: 
    - A relational database was created in Microsoft SQL Server to store the loan data.
2. **Data Analysis and SQL Queries**: 
    - SQL queries were crafted to extract key performance indicators (KPIs), such as total and monthly loan applications, funded amounts, and average interest rates.
3. **Data Processing in Excel**:
    - The dataset was further cleaned, processed, and analyzed using Excel for preliminary insights and data validation.
4. **Categorization of Loans**: 
    - Loans were categorized as 'Good' or 'Bad' based on repayment status.
5. **Temporal and Categorical Analysis**: 
    - Analysis was performed based on issue month, state, loan term, employee length, loan purpose, and home ownership.
6. **Visualization**: 
    - Outputs from SQL queries were visualized using Power BI, Excel, and Tableau to ensure data consistency and provide a graphical representation of the findings.

---

## Key Insights and Findings

- **Total Loan Applications**: A breakdown of the total loan applications and the distinction between MTD (Month-To-Date) and PMTD (Previous Month-To-Date) applications.
- **Total Funded Amount vs. Amounts Received**: Insights into the bank's liquidity and loan performance.
- **Average Interest Rate and DTI (Debt to Income) Ratio**: Analysis to understand the financial health of the borrowers.
- **Loan Categorization**: Segmentation of loans into 'Good' and 'Bad' categories, providing a clear picture of the loan portfolio's risk profile.
- **Detailed Breakdowns**: Analysis by loan status, purpose, state, term, and other factors to identify patterns and trends.

---

## Tools and Technologies Used

- **SQL Management Server**: For database management and data analysis.
- **Excel**: For data cleaning, processing, and preliminary analysis.
- **Power BI**: For data visualization and dashboard creation.
- **Tableau**: For advanced data visualization and interactive dashboards.

---

## Future Work

- **Predictive Modeling**: Forecast loan defaults.
- **Demographic Analysis**: Tailor loan products.
- **Impact of Loan Terms**: Deeper analysis on repayment rates.

---

## Conclusion

This project offers valuable insights into the bank's loan portfolio, highlighting areas of strength and opportunities for improvement. It serves as a robust model for data-driven decision-making in financial services.

---

## Key Visualizations

### Summary Dashboard
![summary](https://github.com/EcoSkull/BANK-LOAN-ANALYSIS/blob/main/summary.jpg)

### Overview Dashboard
![overview](https://github.com/EcoSkull/BANK-LOAN-ANALYSIS/blob/main/overview.jpg)

### Detailed Insights Dashboard
![details](https://github.com/EcoSkull/BANK-LOAN-ANALYSIS/blob/main/details.jpg)

---

## Terminologies Used in Data

| **Field**               | **Purpose**                                                                                                                                          | **Use for Banks**                                                                                                                       |
|-------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------|
| **Loan ID**             | A unique identifier assigned to each loan application or account.                                                                                     | Efficiently manage and track loans throughout their lifecycle, organize loan records, monitor repayments, and address customer inquiries. |
| **Address State**       | Indicates the borrower's location.                                                                                                                   | Identify regional trends in loan demand, adjust marketing strategies, and manage risk portfolios based on geographic regions.            |
| **Employee Length**     | Provides insights into the borrower's employment stability.                                                                                           | Assess a borrower's ability to repay, as stable employment often translates to a lower default risk.                                     |
| **Employee Title**      | Specifies the borrower's occupation or job title.                                                                                                     | Verify income sources, assess the borrower's financial capacity, and tailor loan offers to different professions.                        |
| **Grade**               | Represents a risk classification assigned to the loan based on creditworthiness.                                                                      | Price loans and manage risk, with higher-grade loans typically receiving lower interest rates.                                           |
| **Sub Grade**           | Refines the risk assessment within a grade, providing additional risk differentiation.                                                                | Offer a finer level of risk assessment, helping banks tailor interest rates and lending terms to match borrower risk profiles.           |
| **Home Ownership**      | Indicates the borrower's housing status.                                                                                                              | Assess collateral availability and borrower stability, as homeowners may have lower default rates.                                       |
| **Issue Date**          | Marks the loan's origination date.                                                                                                                    | Track loan aging, calculate interest accruals, and manage loan portfolios.                                                               |
| **Last Credit Pull Date** | Records when the borrower's credit report was last accessed.                                                                                         | Track credit history updates, assess credit risk, and make informed lending decisions.                                                  |
| **Last Payment Date**   | Marks the most recent loan payment received.                                                                                                          | Assess payment behavior, calculate delinquency, and project future payments.                                                             |
| **Loan Status**         | Indicates the current state of the loan (e.g., fully paid, current, default).                                                                         | Monitor loan health, categorize loans for risk analysis, and determine provisioning requirements.                                        |
| **Next Payment Date**   | Estimates the date of the next loan payment.                                                                                                          | Assist in cash flow forecasting, liquidity planning, and revenue projection from loan portfolios.                                        |
| **Purpose**             | Specifies the reason for the loan (e.g., debt consolidation, education).                                                                              | Segment and customize loan offerings, aligning loan terms with borrower needs.                                                           |
| **Term**                | Defines the duration of the loan in months.                                                                                                           | Structure loan agreements, calculate interest payments, and manage loan maturities.                                                      |
| **Verification Status** | Indicates whether the borrower's financial information has been verified.                                                                             | Gauge data reliability, verify income, and evaluate loan application credibility.                                                        |
| **Annual Income**       | Reflects the borrower's total yearly earnings.                                                                                                        | Determine loan eligibility, calculate debt-to-income ratios, and evaluate creditworthiness.                                              |
| **DTI (Debt-to-Income Ratio)** | Measures the borrower's debt burden relative to income.                                                                                     | Assess a borrower's ability to handle loan payments and make responsible lending decisions.                                              |
| **Instalment**          | The fixed monthly payment amount for loan repayment, including principal and interest.                                                                | Structure loan terms, calculate amortization schedules, and assess payment affordability.                                                |
| **Interest Rate**       | Represents the annual cost of borrowing expressed as a percentage.                                                                                    | Price loans, manage profit margins, and attract investors.                                                                               |
| **Loan Amount**         | The total borrowed sum, defining the principal amount.                                                                                                | Determine loan size and manage financial exposure.                                                                                       |


---

## Getting Started

### Prerequisites

- **SQL Management Server**: To manage and query the database.
- **Excel**: For data processing and analysis.
- **Power BI Desktop**: For creating and viewing dashboards.
