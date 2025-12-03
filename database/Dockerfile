FROM postgres:15-alpine

# Copie le script d'initialisation dans le répertoire prévu par PostgreSQL
COPY init.sql /docker-entrypoint-initdb.d/init.sql

# Expose le port standard de PostgreSQL
EXPOSE 5432
