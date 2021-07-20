```sql
DROP TABLE users;

CREATE TABLE users (
  id SERIAL,
  name VARCHAR(128),
  email VARCHAR(128) UNIQUE,
  PRIMARY KEY(id)



```
