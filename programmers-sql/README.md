# Programmers SQL

프로그래머스 SQL 문제를 풀면서

- 헷갈린 개념
- 오답노트
- SQL 문법
- 다시 풀어볼 문제

를 매일 정리하는 저장소입니다.

## 01-Retrieval

- **Column Selection**
  - SELECT

- **Row Selection**
  - DISTINCT
  - LIMIT
  - OFFSET

- **Sorting**
  - ORDER BY

- **Combining Results**
  - UNION
  - INTERSECT
  - EXCEPT

- **Data Source**
  - FROM
  - VIEW
  - TABLE

---

## 02-Filtering
- **Operator ** # 연산자
  - **Comparison**
    - `=`
    - `>`
    - `<`
    - `>=`
    - `<=`
    - `!=`
  
  - **Range**
    - `BETWEEN`
  
  - **Multiple Conditions**
    - `AND`
    - `OR`
    - `NOT`

- **Pattern Matching**
  - `LIKE`
  - `REGEXP`

- **Set Filtering**
  - `IN`
  - `EXISTS`

- **NULL Filtering**
  - `IS NULL`
  - `IS NOT NULL`

---

## 03-Aggregation

- **Aggregate Functions**
  - `COUNT`
  - `SUM`
  - `AVG`
  - `MAX`
  - `MIN`

- **Grouping**
  - `GROUP BY`

- **Group Filtering**
  - `HAVING`

- **Conditional Aggregate**
  - `COUNT(CASE WHEN ...)`
  - `SUM(CASE WHEN ...)`
  - `AVG(CASE WHEN ...)`

- **Advanced Grouping**
  - `WITH ROLLUP`

---

## 04-Transformation

- **NULL Handling**
  - `COALESCE`
  - `IFNULL`
  - `NULLIF`

- **Value Mapping**
  - `CASE WHEN`

- **Type Conversion**
  - `CAST`
  - `CONVERT`

- **String Processing**
  - `CONCAT`
  - `SUBSTRING`
  - `LEFT`
  - `RIGHT`
  - `TRIM`
  - `REPLACE`
  - `LOWER`
  - `UPPER`

- **Numeric Processing**
  - `ROUND`
  - `CEILING`
  - `FLOOR`
  - `ABS`
  - `MOD`

- **Date & Time**
  - `DATE_ADD`
  - `DATE_SUB`
  - `DATEDIFF`
  - `DATE_FORMAT`
  - `YEAR`
  - `MONTH`
  - `DAY`

- **Formatting**
  - `FORMAT`
  - `LPAD`
  - `RPAD`

- **Conditional Logic**
  - `IF`

---

## 05-Combination

- **Joining**
  - `INNER JOIN`
  - `LEFT JOIN`
  - `RIGHT JOIN`
  - `CROSS JOIN`
  - `SELF JOIN`

- **Subquery**
  - Scalar Subquery
  - Inline View
  - Correlated Subquery

- **CTE**
  - `WITH`

---

## 06-Analysis

- **Window Functions**
  - `OVER`
  - `PARTITION BY`

- **Ranking**
  - `ROW_NUMBER`
  - `RANK`
  - `DENSE_RANK`

- **Row Comparison**
  - `LAG`
  - `LEAD`
  - `FIRST_VALUE`
  - `LAST_VALUE`

- **Pivoting**
  - `GROUP_CONCAT`
