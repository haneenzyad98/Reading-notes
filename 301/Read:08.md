# SQLBolt

you can retrieve data from a SQL database by SELECT statements

- SELECT
 
      SELECT column, another_column, …
      FROM mytable;

you can add condition for select statment by WHERE then condtion

- AND.
- OR.
- NOT.
- LIKE.
- NOTLIKE.
- BETWEEN.
- NOTBETWEEN.
- IN.
- NOT IN.

- DISTINCT keyword will blindly remove duplicate row.

-ORDER BY column ASC/DESC.


When  write SELECT * FROM tabelname
it is retrieve all informatin from the tabel

you can select column and retrieve the data 

- INSERT

       INSERT INTO table
       VALUES (value) 
 and you can Choose column 

 - Updating rows

       UPDATE table
       SET column = value
        WHERE condition;

- Deleting rows

      DELETE FROM table
      WHERE condition;

- Creating tables

      CREATE TABLE IF NOT EXISTS table (
       column DataType TableConstraint DEFAULT default_value,
       another_column DataType TableConstraint DEFAULT default_value);

- Altering tables

       ALTER TABLE tablename
       ADD column DataType OptionalTableConstraint 
       DEFAULT default_value;


- Dropping tables


       DROP TABLE IF EXISTS table;







































