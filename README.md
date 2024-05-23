## Sales Insights Data Analysis Project


Detailed Instruction

1. **Retrieve All Customer Records**:
   - Use the `SELECT` statement to fetch all columns from the `customers` table.
   - The `*` symbol denotes all columns.

2. **Count Total Number of Customers**:
   - Use the `COUNT` aggregate function to count the total number of records in the `customers` table.

3. **Retrieve Transactions for Chennai Market**:
   - Use the `SELECT` statement to fetch all columns from the `transactions` table.
   - Filter the records using the `WHERE` clause to specify the `market_code` for Chennai (`'Mark001'`).

4. **Retrieve Distinct Product Codes Sold in Chennai**:
   - Use the `SELECT DISTINCT` statement to fetch unique `product_code` values from the `transactions` table.
   - Filter the records using the `WHERE` clause to specify the `market_code` for Chennai (`'Mark001'`).

5. **Retrieve Transactions in US Dollars**:
   - Use the `SELECT` statement to fetch all columns from the `transactions` table.
   - Filter the records using the `WHERE` clause to specify the `currency` as `'USD'`.

6. **Retrieve Transactions in 2020**:
   - Use the `SELECT` statement to fetch all columns from both `transactions` and `date` tables.
   - Use an `INNER JOIN` to combine records from both tables where the `order_date` matches the `date` column in the `date` table.
   - Filter the records using the `WHERE` clause to specify the `year` as 2020.

7. **Calculate Total Revenue in 2020**:
   - Use the `SUM` aggregate function to calculate the total `sales_amount` from the `transactions` table.
   - Use an `INNER JOIN` to combine records from the `transactions` and `date` tables where the `order_date` matches the `date` column in the `date` table.
   - Filter the records using the `WHERE` clause to specify the `year` as 2020.
   - Ensure the `sales_amount` is calculated for transactions in both `INR` and `USD` currencies.

8. **Calculate Total Revenue in January 2020**:
   - Use the `SUM` aggregate function to calculate the total `sales_amount` from the `transactions` table.
   - Use an `INNER JOIN` to combine records from the `transactions` and `date` tables where the `order_date` matches the `date` column in the `date` table.
   - Filter the records using the `WHERE` clause to specify the `year` as 2020 and the `month_name` as 'January'.
   - Ensure the `sales_amount` is calculated for transactions in both `INR` and `USD` currencies.

9. **Calculate total Revenue in 2020 for Chennai**:
   - Use the `SUM` aggregate function to calculate the total `sales_amount` from the `transactions` table.
   - Use an `INNER JOIN` to combine records from the `transactions` and `date` tables where the `order_date` matches the `date` column in the `date` table.
   - Filter the records using the `WHERE` clause to specify the `year` as 2020 and the `market_code` for Chennai (`'Mark001'`).


