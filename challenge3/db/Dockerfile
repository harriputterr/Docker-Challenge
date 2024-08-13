# db/Dockerfile
FROM mariadb:latest

# Copy the init.sql file to the directory where MariaDB will automatically execute it
COPY ./init/init.sql /docker-entrypoint-initdb.d/
