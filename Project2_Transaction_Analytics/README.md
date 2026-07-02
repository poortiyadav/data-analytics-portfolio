Project 2: Debit & Credit Transaction Analytics Dashboard
Tools: MySQL · SQL · Power BI (DAX) · Tableau · Advanced Excel

Domain: Banking & Financial Services — Transaction Monitoring & Operations Reporting
Business Problem:

Operations and risk teams needed visibility into transaction volumes, branch-level activity, and suspicious transaction patterns. This project builds a monitoring dashboard surfacing key transaction metrics and flagging high-risk activity.
KPIs Tracked:

Total Credit Amount — measures total deposits/inflows
Total Debit Amount — measures total withdrawals/outflows
Credit to Debit Ratio — shows whether bank receives more deposits than withdrawals
Net Transaction Amount — measures net cash flow over a period
Account Activity Ratio — indicates how active a customer is relative to their balance
Transactions per Day/Week/Month — identifies volume trends over time
Total Transaction Amount by Branch — compares branch transaction performance
Transaction Volume by Bank — compares performance across banks
Transaction Method Distribution — shows which methods are most popular
Branch Transaction Growth (%) — identifies growing vs declining branches
High-Risk Transaction Flag — flags transactions exceeding threshold amount
Suspicious Transaction Frequency — counts high-risk transactions by month

SQL Techniques Used:

Window functions: LAG, PARTITION BY for month-over-month growth
NULLIF for safe division to avoid divide-by-zero errors
CASE statements for conditional risk flagging
DATE functions for daily, weekly, monthly trend analysis
Subqueries for risk account segmentation

Files in This Folder:

Banking_Analytics_Project.sql
Debit_and_credit_excel.xlsx
Debit_and_Credit_Power_bi.pbix
Debit_and_Credit_tableau.twbx
