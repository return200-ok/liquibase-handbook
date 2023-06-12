# liquibase-handbook
Liquibase create two tables in your database `databasechangelog` and `databasechangeloglock`. All the scripts executed in the database will store the history in `databasechangelog`. When you ran `tag` process this mark the last script executed with the version you sent in the column `tag`.
