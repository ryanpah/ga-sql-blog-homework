# SQL Blog

##Prereqs
- SQL
- Sinatra
- Ruby

## Learning Objectives
- Anatomy of a database (table, row, column, index, etc.)
- Basic understanding that column data types exist and are different
- Develop a level of proficiency with postgres.
- Develop a level of proficiency with psql command line utility.
- Data manipulation, aka DML. (SELECT, INSERT etc.)
- Data definition, aka DDL. (CREATE TABLE, ADD COLUMN, etc.)
- Use SQL scripts to load/manipulate data

## Requirements
We are going to create a Blog using Sinatra and SQL. This Blog will have a set of Posts.

### Step 1, Create a Database named blog
- Use the psql command line utility for this.


### Step 2, Create a Posts table with the following columns:
*Create the SQL in the setup_ddl.sql file, and load this file into the DB using psql.*

- id *(primary key)*
- subject *(Subject text of this Post)*
- contents *(Post)*
- created_at *(time when this Post was created)*

### Step 3, Populate the Database with Posts
*Create the SQL in the setup_dml.sql file, and load this file into the DB using psql.*

- **Note: This SQL is created in the setup_dml.sql file!!**

### Step 4, Create a Sinatra app that will:
- Use the [pg gem](https://bitbucket.org/ged/ruby-pg/wiki/Home) to connect to the blog database.
- Use the pg gem to execute the SQL that will read the posts from the database.
- Show all the posts in the database.

#### Extra:
- Use Sinatra to create, update and delete posts.
- Create a setup_ddl.rb and setup_dml.rb that will use the Ruby and pg gem to populate the database.


## Help
#### [SQL QuickRef](http://http://www.w3schools.com/sql/sql_quickref.asp)
#### [Simply SQL Book](https://docs.google.com/viewer?url=http%3A%2F%2Ffiles.joshuaharper.com%2FWebsites_files%2FCode%2520Resources%2FeBooks%2FPHP_MySQL_XML%2FSimply_SQL.pdf)
#### [Data Definition Language (DDL)](http://http://www.postgresql.org/docs/9.3/static/ddl.html)
#### [Data Manipulation Language (DML)](http://www.postgresql.org/docs/9.3/static/dml.html)
#### [Data Types](http://www.postgresql.org/docs/9.3/static/datatype.html)
#### [PSQL](http://www.postgresql.org/docs/9.3/static/app-psql.html)
#### [PSQL Cheat Sheet](http://cheat.errtheblog.com/s/postgresql)
