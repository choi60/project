FROM mariadb:10.5

COPY 50-server.cnf /etc/mysql/mariadb.conf.d/50-server.cnf
ENV MYSQL_ROOT_PASSWORD=password
ENV MYSQL_USER=testus
ENV MYSQL_PASSWORD=testpw
ENV MYSQL_DATABASE=testdb
EXPOSE 3000
CMD ["mysqld"]

