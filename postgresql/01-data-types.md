## DATA TYPES

- CHAR(n) \* 64 characters
- VARCHAR(n)
- TEXT
- BYTEA(n) - up to 255 bytes

---

- SMALLINT -32768, +32768
- INTEGER 2 Billion
- BINGINT 10\*\*18 ish

---

- REAL 32 bit 10\*\*38 - 7 digits accuracy
- DOUBLE PRECESION 64 bits 10\*\*308 14 digits accuracy
- NUMERIC(accuracy, decimal) - Specified digits of accuracy and digitd after the decimal points

---

- TIMESTAMP 'YYYY-MM-DD HH:MM:SS'
- DATE 'YYYY-MM-DD'
- TIME 'HH:MM::SS'
- NOW()

Text fields (small and large)
Binary fields (small and large)
Numeric fields
AUTO_INCREMENT fields
String

Fields

Understand character sets and are indexable for searching
CHAR(n) allocates the entire space (faster for small strings where length is known)
VARCHAR(n) allocates a variable amount of space depending on the data length (less space)
