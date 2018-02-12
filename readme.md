# mysql 101  
* mysql is not case sensitive 
* USING UPPERCASE IS GOOD PRACTICE

### to login to mysql

~~~php
mysql -uroot -p
~~~

### to show all databases

~~~php
show databases;
~~~

### to create a database 

~~~php
create database <databaseName>;
~~~

### to use a database 

~~~php
use <dbname>;
~~~

### list all tables 

~~~php
show tables;
~~~

### to create a table 

~~~php
create table <tablename> (
  id int(11) auto_increment primary key, 
  name varchar(30) not null,
  email varchar(30)
);
~~~

### to know structure of table 

~~~php
describe <tableName>;
~~~


### insert into database 

~~~php
insert into <tableName> (<column1>, <column2>) values('column1_value', 'column2_value'); 
~~~

### retrieve/read data from database 

~~~php
select <column> from <tablename>;

### for getting all results 
select * from <tablename> ;
~~~

### Update database value

~~~php
update <tableName> set <columnName>=<columnValue> where id=<somevalue>;
~~~

### delete table row

~~~php
delete from <tableName> where <columnName>=<columnValue>;
~~~












