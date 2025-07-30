FROM mysql:8.0

ENV MYSQL_ROOT_PASSWORD=rootpassword
ENV MYSQL_DATABASE=sakila

COPY ./*.sql /docker-entrypoint-initdb.d/
