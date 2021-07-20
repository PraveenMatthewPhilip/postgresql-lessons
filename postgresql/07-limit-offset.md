```sql
SELECT * FROM users ORDER BY email DESC LIMIT 2;
SELECT * FROM users ORDER BY email OFFSET 1 LIMIT 2;
```

Note: The OFFSET starts from row 0
The WHERE and ORDER BY clauses happen _before_ the LIMIT / OFFSET are applied.
