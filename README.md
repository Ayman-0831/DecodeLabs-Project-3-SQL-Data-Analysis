# DecodeLabs-Project-3-SQL-Data-Analysis
SQL Data Analysis project using Microsoft Access
## Database File
- `Project 3 SQL Analysis.accdb`

## SQL Concepts Used
In this project I have used the following SQL commands:
1. **SELECT** - To retrieve data
2. **WHERE** - To apply conditions
3. **ORDER BY** - To sort data
4. **DISTINCT** - To remove duplicates
5. **AVG / SUM** - To calculate average and total
6. **GROUP BY** - To group data
7. **COUNT** - To count records

## Sample Queries
```sql
SELECT * from orders;
SELECT *
FROM ORDERS
WHERE Quantity > 3;
SELECT *
FROM ORDERS
ORDER BY TotalPrice DESC;
