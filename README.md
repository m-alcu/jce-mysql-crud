# Atlassian Connect App using Express

Example to manage a mysql CRUD inside an application from atlassian connect app.

Previous instructions

1) Install mysql instance. Try for example docker

docker run -p 3306:3306 --name some-mysql -e MYSQL_ROOT_PASSWORD=my-secret-pw -d mysql:latest

2) Execute db.sql inside instance.

3) Allow permissions to app to access instance

ALTER USER 'root'@'%' IDENTIFIED WITH mysql_native_password BY 'my-secret-pw';
