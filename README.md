docker run -p 3306:3306 --name mysql57 -e MYSQL_ROOT_PASSWORD=admin -d -v ~/Workspace/Docker/mysql/InitScript:/docker-entrypoint-initdb.d hhzz/mysql57
