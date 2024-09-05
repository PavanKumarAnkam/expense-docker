FROM mysql:8.0
COPY scripts/*.sql /docker-entrypoint-initdb.d/
ENV MYSQL_ROOT_PASSWORD=ExpenseApp@1 \
    MYSQL_USER=expense \
    MYSQL_PASSWORD=ExpenseApp@1 \
    MYSQL_DATABASE=transactions