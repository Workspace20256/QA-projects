# Basic SQL Queries for QA Practice
# Sample Users Table

| id | name | email | country | status | created_at |
|---|---|---|---|---|---|
| 1 | Example Smith | Example1@gmail.com | UK | active | 2026-01-10 |
| 2 | Example Lee | Example2@gmail.com | Sweden | inactive | 2026-02-14 |
| 3 | Example Brown | Example3@gmail.com | USA | active | 2026-03-01 |
| 4 | Example Kim | Example4@gmail.com | NZ | active | 2026-03-12 |
| 5 | Example Wilson | Example5@gmail.com | UAE | blocked | 2026-04-05 |

---

## Example Query

```sql
SELECT * FROM users
WHERE country = 'Korea';
```

## Select all users
```sql
SELECT * FROM users;
```
## Find user by email
```sql
SELECT * FROM users
WHERE email = 'Example1@gmail.com';
```
## Count all users
```sql
SELECT COUNT(*) FROM users;
```
## Find users from specific country
```sql
SELECT * FROM users
WHERE country = 'UK';
```
## Sort users by registration date
```sql
SELECT * FROM users
ORDER BY created_at DESC;
```
## Find active users
```sql
SELECT * FROM users
WHERE status = 'active';
```
