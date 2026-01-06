# DATA_ANALYSIS_WITH_COMPLEX_QUERIES

**COMPANY**: CODTECH IT SOLUTIONS

**NAME**: ONKAR SABALE

**INTERN ID**: CT04DG2885 

**DOMAIN**: SQL

**Task Description**:
1) What Are Complex SQL Queries?
       - A complex SQL query is any query that goes beyond simple SELECT, FROM, and WHERE statements. It typically involves multiple layers of logic, such as:
Joining multiple tables
       - Using subqueries we can
     1) Creating CTEs (Common Table Expressions)
     2) Applying window functions
     3) Including aggregations, filters, and sorting
     4) Handling duplicate data, nulls, or hierarchies
        
2) What is a Window Function in SQL?
         - A window function performs a calculation across a set of table rows that are related to the current row, but does not collapse the result into a single output like GROUP BY does.
         - window  functions :
            1) ROW_NUMBER()
            2) RANK()
            3) DENSE_RANK()
            4) SUM()
            5) AVG()
            6) LAG() / LEAD()
  
3) What is a Subquery in SQL?
          - A subquery (also called an inner query or nested query) is a query inside another query. It returns a value or a set of values that the outer query uses.
          - Subqueries allow you to build queries in layers, solving complex problems step by step. 
          - Types :
             1) Scalar Subquery
            2) Row Subquery
            3) Table Subquery
            4) Correlated Subquery
4) What is a CTE (Common Table Expression) in SQL?
           - A CTE (Common Table Expression) is a temporary result set that you define at the start of a query using the WITH keyword. It's like creating a named subquery that you can reuse or layer within a main query.
