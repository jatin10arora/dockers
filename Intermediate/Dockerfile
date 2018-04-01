# Use an official tomcat runtime as a parent image
FROM tomcat:8.0.50-jre8

#Copy WAR file
COPY ./login/login.war /usr/local/tomcat/webapps/login.war


# Make port 8080 available to the world outside this container
EXPOSE 8080

# Run catalina.sh when the container launches
CMD ["catalina.sh", "run"]
