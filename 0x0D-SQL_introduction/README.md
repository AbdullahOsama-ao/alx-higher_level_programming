# Introduction For (Structured Query Langugae)

## Concepts ...
- SQL => Structured Query Language
- DDL => Data Definition Language, It is a portion of (SQL) That deals with Structure itself.
- DML => Data Manipulation Language, It is a portion of (SQL) That deals with Data inside the Strucutre.

## How to install sql on Sandbox (Ubuntu 20.4) ...
- sudo apt update, then
- sudo apt install mysql-server, then
- apt-get update =>this is optional (to correct some problems), then
- mysql --version, then
- service mysql start, then
- cat 0-list_databases.sql | mysql -uroot -p =>(optional), then
- sudo mysql =>(to start sql)

## sql Commands ...
- help or '\h' =>for help
- '\c' =>clear the current input statement
- quit =>quit sql