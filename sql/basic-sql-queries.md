# Basic SQL Queries for QA Practice
# Sample Users Table

| id | name | email | country | status | created_at |
|---|---|---|---|---|---|
| 1 | Example Smith | Example@gmail.com | UK | active | 2026-01-10 |
| 2 | Example Lee | Example@gmail.com | Sweden | inactive | 2026-02-14 |
| 3 | Example Brown | Example@gmail.com | USA | active | 2026-03-01 |
| 4 | Example Kim | Example@gmail.com | NZ | active | 2026-03-12 |
| 5 | Example Wilson | Example@gmail.com | UAE | blocked | 2026-04-05 |

---

## Example Query

```sql
SELECT * FROM users
WHERE country = 'Korea';
```

## Select all users
```sql
SELECT * FROM users;

## Find user by email
SELECT * FROM users
WHERE email = 'test@gmail.com';

## Count all users
SELECT COUNT(*) FROM users;

## Find users from specific country
SELECT * FROM users
WHERE country = 'Korea';

## Sort users by registration date
SELECT * FROM users
ORDER BY created_at DESC;

## Find active users
SELECT * FROM users
WHERE status = 'active';
