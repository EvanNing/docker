docker pull mysql
docker run --name pwc-mysql -e MYSQL_ROOT_PASSWORD=123456 -p 3306:3306 -d mysql
