# Database_Normalization
Normalization a database to reduce redundancy and data manipulation errors

# Tools
MS Excel

# WOrk Done
A database containing a single table was submitted for normalization.
Problems
1. Columns with multiple row values (Non-atomic values)
2. Partial dependancy
3. Transitive dependanct

Solutions
1. Columns containing rows with two values were split into two distinct columns.
2. Partial dependancy handled by creating new tables of columns exhibiting partial dependancy and maintaining referential integrity.
3. Transitive dependancy was handled by resolving nonprime attributes that depend on other nonprime attributes in a chain of dependancies.