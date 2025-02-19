# Apply filters to SQL queries

## Project description

This is a project aimed to showcased ability on applying filters to SQL queries. This project aims to show the understanding on basic SQL syntax.

## Retrieve after hours failed login attempts

In order to retrieve afterhour failed login from all the login attempts, following code is used.

Select \*    
From log\_in\_attempts    
Where log\_in\_time \> ‘18:00’  AND success \= ‘FALSE’

## Retrieve login attempts on specific dates

In order to retrieve login attempts on specific dates, following code is used to apply filter on data set.

Select \*    
From log\_in\_attempts    
Where log\_in\_date \= ‘2025-02-10’

## Retrieve login attempts outside of Mexico

This will showcase the usage of NOT inside SQL.

Select \*    
From log\_in\_attempts    
Where  NOT country LIKE ‘MEX@’

‘MEX@’ is used to included both MEX and MEXICO.

## Summary

Applying filters on SQL make life easier when dealing with database. Hope the above pratice shows clearly some basic usage on SQL.  
