# 🗄️ SQL Learning Journey

## Day 05

---

# 📚 Topics Covered

- UPDATE Statement
- DELETE Statement
- Updating Multiple Records
- Conditional Updates
- Deleting Records
- Practice Questions

---

# 📖 Theory

## UPDATE

The UPDATE statement is used to modify existing records in a table.

### Syntax

```sql
UPDATE table_name
SET column_name = value
WHERE condition;
```

Example:

```sql
UPDATE users
SET salary = salary + 10000
WHERE salary < 60000;
```

---

## DELETE

The DELETE statement removes records from a table.

### Syntax

```sql
DELETE FROM table_name
WHERE condition;
```

Example:

```sql
DELETE FROM users
WHERE id = 10;
```

---

# ⚠ Important Notes

- Always use a **WHERE** clause while using UPDATE or DELETE.
- Without WHERE, every row in the table will be updated or deleted.

---

# 💻 Practice

✔ Update single record

✔ Update multiple records

✔ Increase salary using UPDATE

✔ Delete one record

✔ Delete multiple records

✔ Practice different WHERE conditions

---

# 🌸 What I Learned Today

- UPDATE modifies existing data.
- DELETE removes records from a table.
- WHERE is very important while using UPDATE and DELETE.
- Practice improves SQL query writing.

---

## 🎯 Skills Practiced

- UPDATE
- DELETE
- WHERE
- Data Modification
- Query Writing

---

## ⭐ Status

✅ Theory Completed

✅ Practice Completed

---

**Author:** Prachi

**Day:** 05
