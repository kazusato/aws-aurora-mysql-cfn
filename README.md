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

