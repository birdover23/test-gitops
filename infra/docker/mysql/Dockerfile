FROM mysql/mysql-server:5.7
LABEL maintainer="ucan-lab <yes@u-can.pro>"

ENV TZ=UTC

RUN mkdir /var/log/mysql
RUN chown mysql:mysql /var/log/mysql

COPY ./infra/docker/mysql/my.cnf /etc/my.cnf