# 🗄️ SQL Learning Journey

## Day 06 - Constraints

---

# 📚 Topics Covered

- Constraints
- UNIQUE
- NOT NULL
- CHECK
- DEFAULT
- PRIMARY KEY
- AUTO_INCREMENT

---

# 📖 What are Constraints?

Constraints are rules applied to table columns to maintain the accuracy and integrity of data.

---

# 1. PRIMARY KEY

- Uniquely identifies each row.
- Cannot contain NULL values.
- Cannot contain duplicate values.
- Only one PRIMARY KEY is allowed in a table.

Example:

```sql
student_id INT PRIMARY KEY
```

---

# 2. UNIQUE

- Prevents duplicate values.
- Allows only unique data.
- NULL values are allowed (depending on the database).

Example:

```sql
email VARCHAR(100) UNIQUE
```

---

# 3. NOT NULL

- Ensures that a column cannot have NULL values.

Example:

```sql
name VARCHAR(50) NOT NULL
```

---

# 4. CHECK

- Restricts values according to a condition.

Example:

```sql
age INT CHECK(age >= 18)
```

---

# 5. DEFAULT

- Assigns a default value when no value is provided.

Example:

```sql
city VARCHAR(30) DEFAULT 'Pune'
```

---

# 6. AUTO_INCREMENT

- Automatically generates unique numbers.
- Mostly used with PRIMARY KEY.

Example:

```sql
student_id INT AUTO_INCREMENT PRIMARY KEY
```

---

# Example Table

```sql
CREATE TABLE students(
    student_id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(50) NOT NULL,
    age INT CHECK(age >= 18),
    email VARCHAR(100) UNIQUE,
    city VARCHAR(30) DEFAULT 'Pune'
);
```

---

# Summary

| Constraint | Purpose |
|------------|---------|
| PRIMARY KEY | Uniquely identifies each row |
| UNIQUE | Prevents duplicate values |
| NOT NULL | Prevents NULL values |
| CHECK | Restricts values using a condition |
| DEFAULT | Assigns a default value |
| AUTO_INCREMENT | Automatically generates unique numbers |

---

# 🌸 What I Learned Today

- Constraints improve data integrity.
- PRIMARY KEY is unique for every row.
- UNIQUE prevents duplicate values.
- NOT NULL makes a field mandatory.
- CHECK validates data.
- DEFAULT provides a predefined value.
- AUTO_INCREMENT generates IDs automatically.

---

## ⭐ Status

✅ Theory Completed

✅ Practice Completed

---

**Author:** Prachi

**Day:** 06
