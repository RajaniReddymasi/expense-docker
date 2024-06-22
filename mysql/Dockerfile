FROM mysql:8
ENV MYSQL_ROOT-PASSWORD=ExpenseApp@1 \
    MYSQL_USER=Expense \
    MYSQL_PASSWORD=ExpenseApp@1 \
    MYSQL_DATABASE=transactions
COPY scripts/*sql /docker-entrypoint-initdb.d/
