# MySQL

## Installation

https://linuxize.com/post/how-to-install-mysql-on-ubuntu-20-04/

https://www.krizna.com/ubuntu/install-mysql-workbench-ubuntu-20-04/

https://oofloo.com/uninstall-mysql-ubuntu/

### MySQL-Server

https://www.digitalocean.com/community/tutorials/how-to-install-mysql-on-ubuntu-20-04

### MySQL Workbench

https://computingforgeeks.com/install-and-use-mysql-workbench-on-ubuntu/

### Error with root@localhost - solve by creating admin@localhost

MySQL 5.7 and up don't support connecting as "root" in mysql-workbench so you must create a normal user and connect via that.

sudo mysql -u root -p
Create a user named "admin" and use that to connect in mysql-workbench.

CREATE USER 'admin'@'localhost' IDENTIFIED BY 'password';
GRANT ALL PRIVILEGES ON *.* TO 'admin'@'localhost' WITH GRANT OPTION;

### Changing MySQL User Password
https://www.cyberciti.biz/faq/mysql-change-user-password/

## Error

https://askubuntu.com/questions/773446/unable-to-connect-via-mysql-workbench-to-localhost-in-ubuntu-16-04-passwordless
