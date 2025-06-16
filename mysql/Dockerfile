FROM mysql:8.0
ENV MYSQL_ROOT_PASSWORD=ExpenseApp@1
#Copy all SQL scripts from the "scripts" directory into the Docker image during container initialization if placed in /docker-entrypoint-initdb.d
ADD scripts/*.sql /docker-entrypoint-initdb.d 