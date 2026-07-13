## 비교연산

---

- **기본문법:**
```sql
WHERE col ⟪비교연산자⟫ cond
```

- **비교연산자** : `=` `>` `<` `>=` `<=` `!=`

- **사용예시**
```sql
SELECT *
FROM EMPLOYEE
WHERE SALARY >= 5000;
```
## 범위연산

---
- **기본문법:**
```sql
WHERE col BETWEEN cond1 AND cond2
```

- **사용예시**
```sql
SELECT COUNT(*) AS CNT
FROM USER_INFO
WHERE JOINED BETWEEN '2021-01-01' AND '2021-12-31'
```
- **잘못된예시**
```sql
WHERE cond1 <= col <= cond2
```
