## LIMIT

---

- **기본문법:**
```sql
SELECT col
FROM table
WHERE cond
ORDER BY col ASC/DESC
LIMIT N
```

## 기타 최대/최솟값 조회

---
- **최댓값 필요한 경우**: MAX(col)
- **사용예시**
```sql
SELECT MAX(col) AS 최댓값
FROM table
WHERE cond
```

- **최댓값이 존재하는 행이 필요한 경우**: TOP N, LIMIT
- **사용예시(SQL Server)**
```sql
SELECT TOP N *
FROM table
WHERE cond
ORDER BY col ASC/DESC
```
