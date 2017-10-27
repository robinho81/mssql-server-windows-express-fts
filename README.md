# mssql-server-windows-express-fts
Dockerfile to create a container with SQL Server express installed and Full Text Search on. 

Steps to run:-
1. docker build -t sql-server-windows-express-fts
2. docker run -d -p 1433:1433 -e sa_password=MyTestSaPassw0rd -e ACCEPT_EULA=Y sql-server-windows-express-fts


