FROM mariadb:latest

ENV MYSQL_DATABASE=laravel \
  MYSQL_USER=admin \
  MYSQL_PASSWORD=xS0N0kOkuf \
  MYSQL_ROOT_PASSWORD=xS0N0kOkuf \
  TZ=Asia/Tokyo

COPY ./my.cnf /etc/mariadb/conf.d/my.cnf
RUN chmod 644 /etc/mariadb/conf.d/my.cnf