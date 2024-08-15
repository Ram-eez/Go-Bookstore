Used mySQL to Create the database and the table sperately.
```
CREATE DATABASE simplerest;
USE simplerest;

CREATE TABLE books (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(255) NOT NULL,
    author VARCHAR(255) NOT NULL,
    publication VARCHAR(255) NOT NULL
);
```
