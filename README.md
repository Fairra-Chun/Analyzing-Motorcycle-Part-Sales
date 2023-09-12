# Analyzing-Motorcycle-Part-Sales
Create a query to return product_line, the month from date, displayed as 'June', 'July', and 'August', the warehouse, and net_revenue.

net_revenue is calculated by getting the sum of total and multiplying by 1 - payment_fee, rounding to two decimal places.
You will need to filter client_type so that only 'Wholesale' orders are returned.
The results should first be sorted by product_line and month in ascending order, then by net_revenue in descending order.
Note: Please also ensure that you do not change the name of the DataFrame that the query result will be saved as - creating new cells in the Workspace will produce a DataFrame with a different name. Make sure that your final solution uses the names provided: revenue_by_product_line (see image below).
