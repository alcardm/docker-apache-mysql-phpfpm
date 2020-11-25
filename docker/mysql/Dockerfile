FROM mysql:5.7

ARG MYSQL_CONTAINER_USER
ARG MYSQL_CONTAINER_GROUP

RUN sed -i "s/#log-error/log-error/g" /etc/mysql/mysql.conf.d/mysqld.cnf

RUN usermod -u 1000 ${MYSQL_CONTAINER_USER} \
    && groupmod -g 1000 ${MYSQL_CONTAINER_GROUP}

# Copy a database script
# Should include create database statement
# COPY database.sql /docker-entrypoint-initdb.d/init.sql