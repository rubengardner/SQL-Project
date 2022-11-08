Shell command for this project:

wget https://raw.githubusercontent.com/lerocha/chinook-database/master/ChinookDatabase/DataSources/Chinook_PostgreSql.sql
Downloads the database from the internet

set_pg 
Set the environment for installing PostgreSQL

psql
Launch postegreSQL

\l
Database overview

\c chinook
Connects to chinook database

\i Chinook_PostgreSql.sql
Installs our file to the database

\q 
Exits the server

psql -d chinook
Especifies what database to initialize

\dt

Four methods:
1) Command line interface. Native SQL comands
2) PsycoPG
3) Expression Langugae using SQLAlchemy's Core component
4) SQLAlchemy's full ORM. Class based models.

CRUD Functionality:
Create
Read
Update
Delete