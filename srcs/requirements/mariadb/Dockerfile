FROM mariadb:10.5

ENV MYSQL_ROOT_PASSWORD=${MYSQL_ROOT_PASSWORD}
ENV MYSQL_DATABASE=${MYSQL_DATABASE}
ENV MYSQL_USER=${MYSQL_USER}
ENV MYSQL_PASSWORD=${MYSQL_PASSWORD}

# Copie un script d'init si tu veux ajouter des instructions SQL au démarrage (facultatif)
# COPY ./conf/init.sql /docker-entrypoint-initdb.d/

EXPOSE 3306

