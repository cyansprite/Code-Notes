# SQL
##### Note, doesn't need to be only on one line but MUST end with ;
##### Note syntax : ~filler text~
##### Note syntax :  |optional|
```sql
Main |Type| ~column~ from ~table~ |what|;
```

## Main Command
```sql
    SELECT - extracts data from a database
    UPDATE - updates data in a database
    DELETE - deletes data from a database
    INSERT INTO - inserts new data into a database
        - Must include all that are not auto/nullable
        - Uses Values ();
    CREATE DATABASE - creates a new database
    ALTER DATABASE - modifies a database
    CREATE TABLE - creates a new table
    ALTER TABLE - modifies a table
    DROP TABLE - deletes a table
    CREATE INDEX - creates an index (search key)
    DROP INDEX - deletes an index
```

## What Command
```sql
    FROM  ~tablename~
    WHERE=~conditon~
        - Null is special use like
            - WHERE column_name IS NULL
            - WHERE column_name IS NOT NULL
    ORDER BY ~column|ASC|DESC|~
    VALUES (~value based on column from insert into~, ~...~); 
```

### Where Operators
##### Note: Use () to make bool logic with And and Or
| Operator | Description|
| ----------- | -----|
| = 	      | Equal|
| <>	      | Not equal|
| > 	      | Greater than|
| < 	      | Less than|
| >= 	      | Greater than or equal|
| <= 	      | Less than or equal|
| BETWEEN     | Between an inclusive range|
| LIKE 	      | Search for a pattern|
| IN 	      | To specify multiple possible values for a column|
| AND         | if all the conditions separated by AND is TRUE|
| OR          |  if any of the conditions separated by OR is TRUE|
| NOT         |  if the condition(s) is NOT TRUE|

## Type Command
```sql
    DISTINCT - No Dups
    COUNT( |Type| *) - Returns count
```
