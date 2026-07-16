## 상위 N개 레코드 조회
- **최댓값이 존재하는 행이 필요한 경우**: LIMIT N, TOP N
---

- **사용예시(LIMIT - MySQL):**
```sql
SELECT col
FROM table
WHERE cond
ORDER BY col ASC/DESC
LIMIT N
```
- **사용예시(TOP N - SQL Server)**
```sql
SELECT TOP N *
FROM table
WHERE cond
ORDER BY col ASC/DESC
```

## 최댓값 조회

---
- **최댓값 필요한 경우**: MAX(col)
- **사용예시**
```sql
SELECT MAX(col) AS 최댓값
FROM table
WHERE cond
```
