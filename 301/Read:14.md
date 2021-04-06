# Database normalization

Database normalization is a process
used to organize a database into tables and columns.


## Reasons for Normalization:

- to minimize duplicate data.
- minimize or avoid data modification issues.
- to simplify queries.

There are three common forms of normalization: 1st, 2nd, and 3rd normal form. 

First Normal Form 
- The information is stored in a relational table and each column contains atomic values, and there are not repeating groups of columns.

Second Normal Form 
- The table is in first normal form and all the columns depend on the table’s primary key.

Third Normal Form 
- The table is in second normal form and all of its columns are not transitively dependent on the primary key.