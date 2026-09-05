# ClassicModels Sales & Customer Analysis (SQL)

A SQL project where I analyzed a sample sales database to answer real
business questions — like a data analyst would on the job.

## About the Project

I used the classicmodels sample database (a fictional company that sells
model cars, planes, and other scale models) to practice pulling real
business insights using SQL — not just writing queries, but figuring out
what the numbers actually mean.

## Dataset

Tables used: customers, orders, orderdetails, products, payments, employees.

- 122 customers
- 326 orders
- 110 products
- Data covers January 2003 to May 2005

## Tools Used

MySQL, using SQL joins, subqueries, CTEs, and window functions
(RANK, DENSE_RANK, ROW_NUMBER).

## Questions I Answered

- Who are the top 10 customers by revenue?
- Which customers never placed an order?
- How are customers and revenue spread across countries?
- What's the monthly/yearly revenue trend?
- Which product line makes the most (and least) money?
- What's the average order value?
- Were any orders shipped late?
- What are the top-selling products?
- Which products were never ordered?
- Who's the best-selling product in each product line?
- How does profit margin differ by product line?
- Who are the top customers in each city/state?
- Which customers order often enough to be loyalty candidates?
- Which sales rep brings in the most revenue?
- Is the customer workload fair across sales reps?
- When did total revenue cross $1M and $5M?

## What I Found

- The top 10 customers make up about **28%** of all revenue — the business
  depends a lot on a small group of big customers.
- **24 customers (about 1 in 5) have never ordered anything** — that's a
  good group to target for outreach.
- **Classic Cars** is the best-selling product line, bringing in about
  **40%** of total revenue. **Trains** is the weakest, at under 2%.
- Almost every product has been ordered at least once — only 1 product
  never sold, so there isn't much dead stock.
- Late shipping barely happens — only 1 out of 312 orders shipped late.
- Sales reps don't perform equally even with a similar number of
  customers — one rep brought in $1.26M while another with almost the
  same number of customers brought in only $347K.
- Total revenue passed $1M by mid-2003 and $5M by mid-2004, ending at
  about $9.6M overall.

## What I'd Do Next

- Build a simple dashboard (Power BI) to visualize these numbers
- Look into why some sales reps outperform others
- Come up with a plan to win back the dormant customers

## Author

Harman — [github.com/2004parmeet](https://github.com/2004parmeet)
