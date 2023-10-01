# database-decomposer
A relational database investigation tool to assist rewrite and ETL activities.

For a given relational database with a sufficiently privileged user,  cycle through the 
metadata for all the tables and columns. For each table, analyze the features and usage. 
For each column in each table, analyze and summarize the data, frequency analysis, and more.
Record the findings.

The goal is to provide a snapshot of the use of the tables and columns, not
just a ERWin diagram (which is an important companion piece).
This table and column data-level analysis snapshot is then used to estimate, plan and execute an ETL project.

Designed to operate on recent versions of mySql/MariaDB, MS SQL Server, and Oracle databases.
Other databases may be added in the future.

The analysis output is stored in a SqlLite database. 

Post-process reporting tools to follow.
