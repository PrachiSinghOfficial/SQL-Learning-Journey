# 🗄️ SQL Learning Journey

## Day 02 – Tables, Data Types & Constraints

### 📚 Topics Covered

- SELECT Statement
- DROP Statement
- Data Types
- Constraints
- Rename Table

---

# 📖 Theory

## 1. SELECT Statement

The `SELECT` statement is used to retrieve data from a database.

Example:

```sql
SELECT * FROM students;
```

---

## 2. DROP Statement

The `DROP` statement permanently deletes a database, table, or other objects.

Example:

```sql
DROP TABLE students;
```

---

## 3. Rename Table

Used to change the name of an existing table.

Example:

```sql
RENAME TABLE students TO student_details;
```

---

# 📖 SQL Data Types

## INT

Stores whole numbers.

```sql
age INT
```

---

## VARCHAR(100)

Stores variable-length text up to 100 characters.

```sql
name VARCHAR(100)
```

---

## ENUM

Stores one value from a predefined list.

```sql
gender ENUM('Male','Female','Other')
```

---

## DATE

Stores date values.

```sql
date_of_birth DATE
```

---

## TIMESTAMP

Stores date and time.

```sql
created_at TIMESTAMP
```

---

## BOOLEAN

Stores TRUE or FALSE values.

```sql
is_active BOOLEAN
```

---

## DECIMAL(10,2)

Stores exact decimal values.

```sql
salary DECIMAL(10,2)
```

---

# 📖 Constraints

## PRIMARY KEY

Uniquely identifies each row.

```sql
id INT PRIMARY KEY
```

---

## AUTO_INCREMENT

Automatically generates unique IDs.

```sql
id INT AUTO_INCREMENT
```

---

## NOT NULL

Prevents NULL values.

```sql
name VARCHAR(100) NOT NULL
```

---

## UNIQUE

Ensures values are unique.

```sql
email VARCHAR(100) UNIQUE
```

---

## DEFAULT

Assigns a default value.

```sql
created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP
```

```sql
is_active BOOLEAN DEFAULT TRUE
```

---

# 💻 Practical Work

✅ Created tables

✅ Used different SQL data types

✅ Applied constraints

- PRIMARY KEY
- AUTO_INCREMENT
- NOT NULL
- UNIQUE
- DEFAULT

✅ Renamed tables

✅ Used SELECT

✅ Used DROP

---

# 📖 New Vocabulary

| Word | Meaning |
|------|---------|
| Table | Collection of rows and columns |
| Row | Record |
| Column | Field |
| Constraint | Rule applied to data |
| Primary Key | Unique identifier |
| Data Type | Type of data |
| Rename | Change name |
| Drop | Delete permanently |

---

# 🌸 What I Learned Today

- Learned how to create tables.
- Understood SQL data types.
- Learned constraints.
- Used SELECT queries.
- Renamed tables.
- Learned how DROP works.

---

# 🎯 Skills Practiced

- SQL Tables
- Data Types
- Constraints
- SELECT
- DROP
- Rename Table

---

## ⭐ Status

✅ Theory Completed

✅ Practical Completed

---

**Author:** Prachi

**Day:** 02
