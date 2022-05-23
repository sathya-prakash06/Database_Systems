# Database_Systems

- Database Management Systems (DBMS)
- Structured Query Language (SQL)

### The SQL Language

- Used to issue commands to a database
- Used to query a database
- SQL : Structured Query Language
- The SQL standard is around 70's

### SQL Command Types

- DDL : Data Definition Language (Defines admissible database content / schema)
- DML : Data Manipulation Language (Manipulates database content)
- DCL : Data Control Language (assign data access rights)
- TCL : Transaction Control Language (gROUPS sql commands)

## Defing database schemas

- define relations with their schemas
- define constarins restricting admissible content

## Schema Definition in SQL

- CREATE TABLE< table >(< table-def >)
- < table > is the table name
- < table-def > is a list of column definitions

## Primary Key Constraints

- A primary key contraint refers to a single table
- It identifies a subset of columns as key columns
- Fixing values for key columns must identify row
- No two rows have same values in key columns

## Foreign Key Constraints

- A foreign key constraint refers to a two table
- identifies set of foreign key columns in table 1
- maps foreign key columns nto primary key of table 2
- values in foriegn key columns must appear as primary
- maps each row in table 1 to a row from table 2

## Aggregate queries

- can calculate aggregates over all the rows of the result relation.
- COUNT, SUM, AVG, MIN, MAX
- COUNT: for counting rows in the result relation
- SUM: for summing up values in the result relation
- AVG: for calculating average of values in the result relation
- MIN: for finding minimum value in the result relation
- MAX: for finding maximum value in the result relation
