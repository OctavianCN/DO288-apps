FROM mysql:latest

ENV MYSQL_DATABASE test
ENV MYSQL_USER user
ENV MYSQL_PASSWORD pass
ENV MYSQL_ROOT_PASSWORD rootpass

COPY /test.sql /SqlTestTable/
WORKDIR /SqlTestTable
RUN chmod 777 test.sql

