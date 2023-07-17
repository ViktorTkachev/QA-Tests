# Examples of work performed in MySQL Workbench.

[Database dumps used in the example](https://github.com/](https://drive.google.com/drive/u/3/folders/1MC0AttnmlAmugifFlX3hG6pssYZDqpPB)https://drive.google.com/drive/u/3/folders/1MC0AttnmlAmugifFlX3hG6pssYZDqpPB)

### 1. Выведите имя, фамилию персонажей и название книги, которая на них числится

```sql
SELECT c.fname, c.lname, l.book_name 
FROM characters AS c 
JOIN library AS l ON c.book_id = l.book_id;
```

![MySQL](./img/)
