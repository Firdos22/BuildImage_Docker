FROM mysql:latest
ENV MYSQL_ROOT_PASSWORD 123
ENV MYSQL_PASSWORD users
ENV MYSQL_USER p_u_c_s_d
ENV MYSQL_PASSWORD pucsd
ADD data.sql /docker-entrypoint-initdb.d
EXPOSE 3308


