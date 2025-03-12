FROM mysql
ENV MYSQL_ROOT_PASSWORD=Pass@1234
ENV MYSQL_DATABASE=facebook
EXPOSE 3306
COPY init.sql /docker-entrypoint-initdb.d/
CMD ["mysqld"]
