FROM mysql:latest

ENV MYSQL_ROOT_PASSWORD=root_password
ENV MYSQL_DATABASE=mydb
ENV MYSQL_USER=db_user
ENV MYSQL_PASSWORD=db_password

COPY schema.sql /docker-entrypoint-initdb.d/

