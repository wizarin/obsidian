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
     1. WHERE .... (Filters rows)
    SUBQUERY/INTERSECT/UNION/EXCEPT
    3. GROUP BY ....
    4. HAVING .... ( Filters groups of rows)
    5. SELECT ....
    6. ORDER BY .....
    7. LIMIT ....
    8. RETURN RESULT
