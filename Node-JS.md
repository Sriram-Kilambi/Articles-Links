# Node JS

## Official Documentations

https://nodejs.org/en/

## REST API

https://www.smashingmagazine.com/2018/01/understanding-using-rest-api/

## File Upload

https://www.appcoda.com/restful-api-tutorial-how-to-upload-files-to-server/

## Others

https://medium.com/gist-for-js/use-of-res-json-vs-res-send-vs-res-end-in-express-b50688c0cddf

## MYSQL Installation
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
