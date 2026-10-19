 Project Name - Online Bookstore Sales Analysis using PostgreSQL.


 1. Project Overview and Approach -

   Designed a relational database for an online bookstore with three linked tables (Books, Customers, Orders) connected through primary and foreign keys. Imported    the CSV data into PostgreSQL and wrote 20 SQL queries (11 basic, 9 advanced) to answer business questions on sales, customers, and inventory.

- Built the schema with `SERIAL` primary keys and `REFERENCES` foreign keys to maintain data integrity.
- Analyzed sales by genre and author, identified the best-selling and most expensive books, and found repeat customers and top spenders.
- Calculated the total revenue and the stock remaining after fulfilling all orders.

 2. Tools / Methods / Frameworks -

- Tool: PostgreSQL (pgAdmin), CSV data import.
- Database design: Primary keys, foreign keys, table relationships.
- SQL techniques:
  - Filtering with `WHERE`, `BETWEEN`, `DISTINCT`, `ORDER BY` and `LIMIT`
  - Aggregation with `SUM`, `AVG`, `COUNT`, `GROUP BY` and `HAVING`
  - `INNER JOIN` and `LEFT JOIN` across multiple tables
  - `COALESCE` for handling NULLs in inventory calculations

 3. Result / Impact -

- Produced genre-wise and author-wise sales insights that show which categories and writers drive demand.
- Identified the top-spending customer, repeat buyers, and the cities with high-value orders, which can support targeted marketing.
- Calculated the remaining stock per book, which can help avoid stockouts and overstocking.
- Computed total revenue and the most frequently ordered books to support inventory and pricing decisions.

