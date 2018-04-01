# Use an official mysql runtime as a parent image
FROM mysql

COPY ./schema.sql /docker-entrypoint-initdb.d/

# Define environment variable
ENV MYSQL_ROOT_PASSWORD changeme

# Make port 3306 available to the world outside this container
EXPOSE 3306


