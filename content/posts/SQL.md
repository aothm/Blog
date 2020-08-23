+++
title = "SQL Starting "
date = "2019-11-06"
draft = false
pinned = true
image = "/img/m4x.jpg"
+++
# SQL Create Table statement
Syntax

```sql
CREATE TABLE table_name (
    column1 datatype,
    column2 datatype,
    column3 datatype,
   ....
)
```

* The column parameters specify the names of the columns of the table.

* The datatype parameter specifies the type of data the column can hold (e.g. varchar, integer, date, etc.).

* Tip: For an overview of the available data types, go to our complete Data Types Reference.

## SQL CREATE TABLE Example

```sql
CREATE TABLE Persons (
    PersonID    int             PRIMARY KEY IDENTITY,
    LastName    varchar(255)    NOT NULL,
    FirstName   varchar(255)    NOT NULL,
    Address     varchar(255),
    City        varchar(255)
);
```
