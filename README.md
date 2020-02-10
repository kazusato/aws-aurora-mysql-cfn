# MySQL client

1. Download an RPM from 

```
https://dev.mysql.com/downloads/repo/yum/
```

and install by 

```
# yum localinstall mysql80-community-release-el7-3.noarch.rpm
```

1. Install MySQL client by

```
# yum install mysql-community-client
```

1. Connect to RDS by

```
$ mysql -h <RDS-endpoint> -u dbadmin -p myworkdb
```
# create database

# create user

# grant

# create table

# load data


## load data local infile with mysql 8.0 client

Add
```
--local-infile=1
```
in the mysql command.
