FROM mysql:5.7-debian
LABEL "Project"="Vprofile"
LABEL "Author"="David"


ENV MYSQL_USER="admin"
ENV MYSQL_ROOT_PASSWORD="vprodbpass"
ENV MYSQL_DATABASE="accounts"

ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql
