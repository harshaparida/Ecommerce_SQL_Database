# Invoice Data SQL Query Outputs

This project showcases SQL queries performed on the `invoice_data` table. The queries include data retrieval, filtering, aggregation, joins, subqueries, views, and indexing. Screenshots are attached for each query's output.

---

## 📌 Basic Data Query

**Description:** Retrieves the first 200 rows from the invoice data to get an overview of the dataset.

![Invoice Data Output](invoice_data_output_1.png)

---

## 📌 Using SELECT, WHERE, ORDER BY, GROUP BY

### ▶️ Filter by Country
**Description:** Fetches InvoiceNo and Country for records where the country is United Kingdom.

![All Data Output](invoice_data_output_2.png)

### ▶️ Quantity Filter with Ordering
**Description:** Retrieves invoices where quantity is greater than 100 and sorts by UnitPrice in descending order.

![Ordered Data Output](invoice_data_ordered.png)

### ▶️ Group By Country with Count
**Description:** Groups orders by country and shows the number of total orders per country in descending order.

![Grouped Data Output](grouped_by_country.png)

---

## 📌 Creating New Table: Customers

**Description:** Creates a new table of customers with distinct CustomerIDs and a custom name format (e.g., `Customer_12345`).

![Customer Table Output](customers_table.png)

---

## 📌 Using JOINS

### ▶️ INNER JOIN
**Description:** Displays invoice details with customer names where matching CustomerIDs exist.

![Inner Join Output](inner_join_output.png)

### ▶️ LEFT JOIN
**Description:** Retrieves all invoices and adds customer names if available.

![Left Join Output](left_join_output.png)

### ▶️ RIGHT JOIN
**Description:** Retrieves all customers and adds invoice details if available.

![Right Join Output](right_join_output.png)

---

## 📌 Subqueries

### ▶️ Customers from UK
**Description:** Retrieves all invoice records where the customer is from UK using a subquery.

![Subquery Output](subquery_output.png)

### ▶️ Latest Invoice Date
**Description:** Finds invoice records from the latest available date.

![Latest Invoice Output](latest_invoice_output.png)

---

## 📌 Aggregate Functions

### ▶️ Total Revenue
**Description:** Calculates the total sales revenue by multiplying quantity with unit price.

![Total Revenue Output](total_revenue_output.png)

### ▶️ Average Order Value
**Description:** Calculates the total and average order value for each invoice.

![Avg Order Output](avg_order_value_output.png)

---

## 📌 Using Views

### ▶️ Revenue by Country
**Description:** A view showing the total revenue grouped by country.

![Revenue by Country View](revenue_by_country_view.png)

### ▶️ Average Spend per Customer
**Description:** A view showing the average amount spent by each customer.

![Avg Spend View](avg_spend_view.png)

### ▶️ Top 5 Invoices
**Description:** A view listing the top 5 invoices with the highest total amount.

![Top 5 Invoices View](top_5_invoices_view.png)

---

## 📌 Query for Indexing

**Description:** A simple query to fetch the first row, used to trigger indexing or performance checks.

![Indexing Query Output](indexing_query_output.png)

---

## ✅ Conclusion

This README documents and visualizes various SQL operations on an invoice dataset using MySQL. The images illustrate the output of each query, helping readers understand the effects of SQL clauses and operations in practical scenarios.

