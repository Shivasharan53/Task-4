The goal of this project is to understand and apply SQL concepts to extract, analyze, and manage data from a e-commerce database.

| No.   | Topic                             | Description                       | Example                                                     |
| ----- | --------------------------------- | --------------------------------- | ----------------------------------------------------------- |
| **1** | SELECT, WHERE, ORDER BY, GROUP BY | Basic data retrieval and grouping | `SELECT * FROM Customerrs WHERE country='USA';`             |
| **2** | JOINS                             | Combine data from multiple tables | `INNER JOIN`, `LEFT JOIN`, simulated `RIGHT JOIN`           |
| **3** | Subqueries                        | Query inside another query        | Filters using grouped results                               |
| **4** | Aggregates                        | Use of `SUM()` and `AVG()`        | Calculate sales and averages                                |
| **5** | Views                             | Virtual table for analysis        | `CREATE VIEW SalesSummary AS ...`                           |
| **6** | Indexing                          | Optimize query performance        | `CREATE INDEX idx_customer_country ON Customerrs(country);` |
| **7** | Optimization                      | Query tuning with indexes         | Improves performance for large datasets                     |
| **8** | Validation                        | Display results using Pandas      | `pd.read_sql_query("SELECT * FROM table;", conn)`           |
