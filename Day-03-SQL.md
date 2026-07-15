# 🗄️ SQL Learning Journey

## Day 03 – ALTER TABLE & INSERT Statement

### 📚 Topics Covered

- ALTER TABLE
- ADD COLUMN
- DROP COLUMN
- MODIFY COLUMN
- RENAME COLUMN
- Change Column Position
- INSERT INTO
- Insert Single Row
- Insert Multiple Rows

---

# 📖 Theory

## 1. ALTER TABLE

The `ALTER TABLE` statement is used to modify the structure of an existing table.

Example:

```sql
ALTER TABLE students
ADD email VARCHAR(100);
```

---

## 2. ADD COLUMN

Adds a new column to an existing table.

Example:

```sql
ALTER TABLE students
ADD phone VARCHAR(15);
```

---

## 3. DROP COLUMN

Removes an existing column from a table.

Example:

```sql
ALTER TABLE students
DROP COLUMN phone;
```

---

## 4. MODIFY COLUMN

Changes the data type or size of an existing column.

Example:

```sql
ALTER TABLE students
MODIFY email VARCHAR(150);
```

---

## 5. RENAME COLUMN

Changes the name of an existing column.

Example:

```sql
ALTER TABLE students
RENAME COLUMN email TO student_email;
```

---

## 6. Change Column Position

Move a column to a different position.

Move column to the first position:

```sql
ALTER TABLE students
MODIFY email VARCHAR(100) FIRST;
```

Move column after another column:

```sql
ALTER TABLE students
MODIFY email VARCHAR(100) AFTER name;
```

---

# 📖 INSERT Statement

The `INSERT INTO` statement is used to add records into a table.

---

## Insert Single Row

```sql
INSERT INTO students
(id, name, age)

VALUES
(1, 'Prachi', 22);
```

---

## Insert Multiple Rows

```sql
INSERT INTO students
(id, name, age)

VALUES
(2, 'Rahul', 21),
(3, 'Aman', 23),
(4, 'Priya', 20);
```

---

# 💻 Practical Work

✅ Added new columns

✅ Dropped columns

✅ Modified column data types

✅ Renamed columns

✅ Changed column positions

- FIRST
- AFTER

✅ Inserted a single record

✅ Inserted multiple records

---

# 📖 New Vocabulary

| Word | Meaning |
|------|---------|
| Alter | Change the structure |
| Column | A field in a table |
| Modify | Change existing data or structure |
| Rename | Change the name |
| Insert | Add new data |
| Record | A row of data |
| First | First position |
| After | Position after another column |

---

# 🌸 What I Learned Today

- Learned how to modify an existing table.
- Added and removed columns using ALTER TABLE.
- Changed column names and positions.
- Learned how to insert one or multiple records into a table.
- Improved my understanding of table management.

---

# 🎯 Skills Practiced

- ALTER TABLE
- ADD COLUMN
- DROP COLUMN
- MODIFY COLUMN
- RENAME COLUMN
- Change Column Position
- INSERT INTO
- SQL Table Management

---

## ⭐ Status

✅ Theory Completed

✅ Practical Completed

---

**Author:** Prachi

**Day:** 03
