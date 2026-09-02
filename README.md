# Banking-Analytics-Databricks
End-to-end Banking Analytics Platform built on Databricks using Medallion Architecture, PySpark, Delta Lake, and Power BI for scalable data processing and business insights.


### Turning Data into smarter business decisions..

Reporting pages:

1. executive
2. customer and account
3. card and transactions (card + card transactions)
4. loan and loan payments (loan + loan payment)
5. branch and employee (branch + employee)
6. support tickets




page wise filters and kpis :

1. executive overview = (Date / Branch / Customer segment / Account type)

< Total Customers/ Total Accounts/ Total Transactions/ Transaction Value/ Total Loans/ Loan Value/ Total Card Transactions/ Support Tickets >


2. customer and account = (Date / Branch / Customer segment / Account type)

< Total Customers/ Total Accounts/ Accounts per Customer/ Active Accounts/ Multi-Product Customers >


3. transaction = (Date / Branch / transaction type / Account type)

<Total Transactions/ Transaction Value/ Average Transaction Value/ Transactions per Account/ Transactions per Customer>


4. loan and payment = (Date / Branch /loan type / loan status)

<Total Loans/ Loan Portfolio Value/ Average Loan Value/ Total Loan Payments/ Payment Value/ Delayed Payment Rate>


5. card = (Date / Branch / card type / card status)

<Total Cards/ Cards per Customer/ Card Transactions/ Card Transaction Value/ Average Card Transaction>


6. branch = (Date / Branch / region)

<Customers/ Accounts/ Transactions/ Transaction Value/ Loans/ Loan Value/ Support Tickets>


7. customer support = (Date / Branch / ticket category / ticket status)

<Total Tickets/ Tickets per Customer/ Open Tickets/ Closed Tickets/ Average Resolution Time>
