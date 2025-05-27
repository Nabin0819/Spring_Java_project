FROM tomcat:9.0-jdk17-openjdk-slim
COPY target/petclinic.war /usr/local/tomcat/webapps/
COPY mysql-connector-java-8.0.19.jar /usr/local/tomcat/lib/

EXPOSE 8080

