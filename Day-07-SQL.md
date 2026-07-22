# 🗄️ SQL Learning Journey

# Day 07 - Aggregate Functions, GROUP BY & Built-in Functions

---

# 📚 Topics Covered

- COUNT()
- SUM()
- AVG()
- MIN()
- MAX()
- GROUP BY
- LENGTH()
- LOWER()
- CONCAT()
- NOW()
- CURDATE()
- DATEDIFF()
- FLOOR()

---

# 1. Aggregate Functions

Aggregate functions perform calculations on multiple rows and return a single value.

## COUNT()

Counts the total number of records.

```sql
SELECT COUNT(*) AS total_users
FROM users;
```

Count male users

```sql
SELECT COUNT(*) AS male_count
FROM users
WHERE gender='male';
```

---

## SUM()

Returns the total value.

```sql
SELECT SUM(salary)
FROM users;
```

---

## AVG()

Returns average value.

```sql
SELECT AVG(salary)
FROM users;
```

---

## MIN()

Returns minimum value.

```sql
SELECT MIN(salary)
FROM users;
```

---

## MAX()

Returns maximum value.

```sql
SELECT MAX(salary)
FROM users;
```

---

# 2. GROUP BY

Groups rows having the same value.

Example

```sql
SELECT gender,
SUM(salary)
FROM users
GROUP BY gender;
```

---

# 3. String Functions

## LENGTH()

Returns number of characters.

```sql
SELECT LENGTH(name)
FROM users;
```

---

## LOWER()

Converts text to lowercase.

```sql
SELECT LOWER(name)
FROM users;
```

---

## CONCAT()

Joins two or more strings.

```sql
SELECT CONCAT(LOWER(name),id)
AS username
FROM users;
```

---

# 4. Date Functions

## NOW()

Returns current date and time.

```sql
SELECT NOW();
```

---

## CURDATE()

Returns current date.

```sql
SELECT CURDATE();
```

---

## DATEDIFF()

Returns difference between two dates.

```sql
SELECT name,
DATEDIFF(CURDATE(),date_of_birth)
AS days
FROM users;
```

---

# 5. Mathematical Functions

## FLOOR()

Rounds down to nearest integer.

```sql
SELECT salary,
FLOOR(salary)
AS rounded_salary
FROM users;
```

---

# ⭐ Other Useful Mathematical Functions

## CEIL()

Rounds up.

```sql
SELECT CEIL(123.45);
```

---

## ROUND()

Rounds normally.

```sql
SELECT ROUND(123.56);
```

---

## ABS()

Returns absolute value.

```sql
SELECT ABS(-45);
```

---

## MOD()

Returns remainder.

```sql
SELECT MOD(20,3);
```

---

## POWER()

Returns power.

```sql
SELECT POWER(2,5);
```

---

## SQRT()

Returns square root.

```sql
SELECT SQRT(144);
```

---

# ⭐ Other Useful Conditional Functions

## IF()

```sql
SELECT name,
IF(salary>50000,'High','Low')
AS salary_status
FROM users;
```

---

## IFNULL()

```sql
SELECT IFNULL(city,'Unknown')
FROM users;
```

---

## COALESCE()

Returns first non-null value.

```sql
SELECT COALESCE(city,state,country);
```

---

## CASE

```sql
SELECT name,
CASE
WHEN salary>60000 THEN 'High'
WHEN salary>30000 THEN 'Medium'
ELSE 'Low'
END AS salary_category
FROM users;
```

---

# 🌸 What I Learned Today

- Aggregate Functions
- GROUP BY
- String Functions
- Date Functions
- Mathematical Functions
- Conditional Functions

---

## 📌 Summary

| Function | Purpose |
|----------|----------|
| COUNT() | Count rows |
| SUM() | Total |
| AVG() | Average |
| MIN() | Minimum |
| MAX() | Maximum |
| GROUP BY | Group records |
| LENGTH() | Count characters |
| LOWER() | Lowercase text |
| CONCAT() | Join strings |
| NOW() | Current Date & Time |
| CURDATE() | Current Date |
| DATEDIFF() | Difference between dates |
| FLOOR() | Round down |
| CEIL() | Round up |
| ROUND() | Round value |
| ABS() | Absolute value |
| MOD() | Remainder |
| POWER() | Exponent |
| SQRT() | Square root |
| IF() | Conditional value |
| IFNULL() | Replace NULL |
| COALESCE() | First non-NULL |
| CASE | Multiple conditions |

---

## ⭐ Status

✅ Theory Completed

✅ Practice Completed

---

**Author:** Prachi

**Day:** 07
