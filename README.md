# mysql-export-import
Export or import big mysql data through command line in linux system

## Export MySQL database using SSH command line 

* `mysqldump -p -u username database_name > dbname.sql`

To export a single table from your database you would use the following command:

* `mysqldump -p --user=username database_name tableName > tableName.sql`

## IMPORT Database 
* `mysql -p -u username database_name < file.sql`

To import a single table into an existing database you would use the following command:

* `mysql -u username -p -D database_name < tableName.sql`
