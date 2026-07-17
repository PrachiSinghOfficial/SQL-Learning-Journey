# 🗄️ SQL Learning Journey

## Day 04 – WHERE Clause and Data Filtering

---

# 📚 Topics Covered

- WHERE Clause
- Comparison Operators
- NOT EQUAL (!=, <>)
- Greater Than / Less Than
- IS NULL
- IS NOT NULL
- BETWEEN
- IN Operator
- AND Operator
- OR Operator
- ORDER BY
- ASC (Ascending)
- DESC (Descending)

---

# 📖 Theory

## 1. WHERE Clause

The `WHERE` clause is used to filter records based on a condition.

Example:

```sql
SELECT * FROM users
WHERE gender = 'Male';
```

---

## 2. Comparison Operators

| Operator | Meaning |
|----------|---------|
| = | Equal |
| != | Not Equal |
| <> | Not Equal |
| > | Greater Than |
| < | Less Than |
| >= | Greater Than or Equal |
| <= | Less Than or Equal |

---

## 3. IS NULL

Checks rows where a value is missing.

Example:

```sql
SELECT * FROM users
WHERE date_of_birth IS NULL;
```

---

## 4. IS NOT NULL

Returns rows that contain a value.

Example:

```sql
SELECT * FROM users
WHERE date_of_birth IS NOT NULL;
```

---

## 5. BETWEEN

Returns values within a specified range.

Example:

```sql
SELECT * FROM users
WHERE date_of_birth
BETWEEN '1990-01-01' AND '2000-12-31';
```

---

## 6. IN Operator

Checks multiple values in one condition.

Example:

```sql
SELECT * FROM users
WHERE gender IN ('Male', 'Other');
```

---

## 7. Logical Operators

### AND

Both conditions must be true.

```sql
SELECT *
FROM users
WHERE gender='Female'
AND date_of_birth>'1990-01-01';
```

### OR

At least one condition must be true.

```sql
SELECT *
FROM users
WHERE gender='Male'
OR gender='Other';
```

---

## 8. ORDER BY

Sorts records.

### ASC

Ascending order.

```sql
ORDER BY date_of_birth ASC;
```

### DESC

Descending order.

```sql
ORDER BY name DESC;
```

---

# 💻 Practical Work

✅ Practiced WHERE clause

✅ Used comparison operators

✅ Checked NULL values

✅ Used BETWEEN

✅ Used IN operator

✅ Practiced AND & OR conditions

✅ Sorted data using ORDER BY

---

# 📚 New Vocabulary

| Word | Meaning |
|------|---------|
| Filter | Show selected records |
| Condition | Rule for selecting data |
| NULL | Empty value |
| BETWEEN | Value inside a range |
| IN | Match multiple values |
| ASC | Ascending order |
| DESC | Descending order |
| Operator | Symbol used in conditions |

---

# 🌸 What I Learned Today

- Filtered records using WHERE.
- Compared values using different operators.
- Checked NULL and NOT NULL values.
- Used BETWEEN and IN to simplify queries.
- Combined multiple conditions using AND and OR.
- Sorted records using ORDER BY.

---

# 🎯 Skills Practiced

- WHERE Clause
- Comparison Operators
- Data Filtering
- Logical Operators
- Sorting Data

---

## ⭐ Status

✅ Theory Completed

✅ Practical Completed

---

**Author:** Prachi

**Day:** 04
