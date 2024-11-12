"# Bank_Loan_Report" 

# Bank Loan Report Project
This project presents an interactive dashboard for analyzing loan application data. The dashboard provides insights into various aspects of bank loans, including application counts, funded and received amounts, interest rates, loan purposes, and risk analysis. The data is analyzed through SQL queries, and the results are visualized to support decision-making and reporting.

## Project Overview
<br>The Bank Loan Report project is designed to assist financial institutions in monitoring and analyzing loan application data. It allows users to track the volume of loan applications, the amount funded and received, the average interest rate, and the Debt-to-Income (DTI) ratio. The data is segmented by various factors like loan purpose, homeownership status, employee length, and more, providing a comprehensive view of the loan portfolio.
</br>

## Data Sources
<br>The project uses a database (bank_loan_data) containing detailed loan information, including application IDs, loan purpose, ownership status, loan amount, interest rate, funded and received amounts, and issue dates. The data is analyzed through SQL queries, aggregated, and visualized on the dashboard.
</br>

## Features and KPIs
<br>The dashboard includes the following key performance indicators (KPIs):</br>

**Total Loan Applications:** The total count of loan applications in the dataset.

**Total Funded Amount:** The sum of all funded loan amounts.

**Total Amount Received:** The sum of all payments received on loans.

**Average Interest Rate:** The mean interest rate across all loans.

**Average Debt-to-Income (DTI) Ratio:** The average DTI ratio across all loans.
Good and Bad Loan Distribution: Segmentation of loans into 'Good' (fully paid or current) and 'Bad' (charged off) categories.

## Dashboard Structure
1. **Summary Dashboard**

![Summary](Dashboard\SUMMARY.png)

The Summary Dashboard provides an overview of key metrics:

Total Loan Application, Total Funded Amount, and Total Amount Received with month-over-month and month-to-date breakdowns.

Average Interest Rate and Average DTI Ratio.

Good Loan Issued and Bad Loan Issued segments displayed with percentages and amounts.

Loan Status Table showing counts, funded amounts, and received amounts for fully paid, charged-off, and current loans.


**2. Overview Dashboard**
The Overview Dashboard offers a deeper breakdown by various dimensions:

**Loan Applications by Month:** Trend of loan applications throughout the year.

**Loan Applications by State:** Geographic distribution of loan applications.

**Loan Applications by Term:** Distribution of loans based on 36 or 60-month terms.

**Loan Applications by Employee Length:** Analysis based on applicants' employment length.

**Loan Applications by Purpose:** Distribution of loans for different purposes (debt consolidation, credit card refinancing, home improvement, etc.).

**Loan Applications by Home Ownership:** Segmentation based on homeownership status (Rent, Mortgage, Own).

**3. Details Dashboard**

The Details Dashboard provides a granular view of individual loans, showing attributes such as:

**ID:** Unique identifier for each loan.

**Purpose:** Reason for the loan.

**Home Ownership:** Applicant's homeownership status.

**Grade and Subgrade:** Loan grade classification.

**Funded Amount:** Amount funded for the loan.

**Interest Rate and Installment:** Monthly installment and interest rate for each loan.
Amount Received: Total amount received for each loan.



## Filter Options

The dashboard includes filters that allow users to drill down on specific dimensions, such as:

**State:** Filter by applicant's state of residence.
**Grade:** Filter by loan grade.
**Purpose:** Filter by loan purpose.
**Good vs. Bad Loan:** Filter to view only good or bad loans.

## Technology Stack

The project is built with the following technologies:

**SQL:** For querying and aggregating data.
**Power BI**: For creating interactive and visually engaging dashboards.
**Database Management System:** SQL database containing loan application data.

## Setup and Usage

To use the Bank Loan Report dashboard:

Import the bank_loan_data table into your SQL database.

Run the provided SQL queries to create aggregations and KPIs.

Open the Power BI / Tableau file and connect it to your database.

Refresh the data source to populate the dashboard with real-time data.

Use the filters to explore data by different dimensions as per the analysis needs.

## Future Enhancements

Potential enhancements for this project could include:

**Predictive Modeling:** Adding machine learning models to predict loan default risk.
**Automated Data Refresh:** Scheduling automatic data updates for real-time insights.
**Interactive Data Drill-Downs:** Enabling users to click through visual elements for more detailed views.
**Additional KPIs:** Incorporating more financial health indicators, such as profit margins and return on investment for loans.

## Acknowledgments

This project was developed to assist financial analysts and managers in tracking loan performance and identifying trends in loan applications. Special thanks to the data and finance teams for providing valuable feedback during the development process.