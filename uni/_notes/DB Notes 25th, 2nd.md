DQL
     Data query language, used to query a database for information
DML
     Data Modi
DDL
     Data Definition Language
DCL
     Data Control Language


SELECT
     WHERE, GROUP BY, HAVING, ORDER BY
     * adds unnecessary computational strain to the database, don't use in exam. 
     Always retrieve data using attribute/column name
     Always use AS to add aliases when selecting attributes. This also helps with ORDER BY.
     --
     SELECT order of execution:
     1. FROM ....
         (INNER) JOIN .... (table2)
            ON table1.pk1 = table2.pk1
            AND ....
            USING (pk1) has to be same key names
            Only shows the common values
         LEFT JOIN ....
         RIGHT JOIN ....
    2. WHERE table.attribute_name.... attribute = 'value'
    SUBQUERY/INTERSECT/UNION/EXCEPT
    3. GROUP BY ....
    4. HAVING .... ( Filters groups of rows)
    5. SELECT ....
    6. ORDER BY attribute1 ASC, attribute2DESC. The query is sorted by attribute1 and then sub-sorted by attribute2 within A1.
    7. LIMIT (int) is the end of the statement, it is an interesting to choose total rows returned. Does not optimise the query, it simply hides the rest of the search. OFFSET (int) skips the given int of rows.
    8. RETURN RESULT

FROM
Operators for WHERE:
     math Boolean operators
     AND, OR, NOT
     BETWEEN, between two values
     IN(list), NOT IN
     LIKE 'J%' matches data that contains the given pattern
     % is wild operator to indicate any string value. So here we query any string starting with 'J'
     ILIKE case insensitive LIKE

SELECT
CONCAT (attri1, ' ', attri2) AS "attri name"
concatenates multiple string values together 
CONCAT_WS (', ', attri1, attri2, attr3) 
*with separator*, choose separator at the start of parameters.
DISTINCT only returns single instance of duplicate value in table



Regex - regular expressions
     
     