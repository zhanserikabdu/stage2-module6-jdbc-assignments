### Java Database Connectivity assignment

1. You need to create a postgresql database called "myfirstdb" binding on port 5432. The database should contain information about users: unique identifier(Id), user first name, user last name and age.(table name - myusers; with the column: id, firstname, lastname, age)
2. Implement class _CustomConnector_ to get connection with "myfirstdb" database.
3. Implement class _CustomDataSource_ using singleton pattern to get connection with "myfirstdb" database 
4. Implement class _SimpleJDBCRepository_, resolve all class methods for create, update, delete and search Users. Use _CustomDataSource_ and _CustomConnector_
for performing statement or prepareStatement to database. 