FROM mysql:8.0.33
LABEL "AUTHOR"="Pavan"

ENV MYSQL_ROOT_PASSWORD="vprodbpass"
ENV MY_SQL_DATABASE="accounts"

ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql
