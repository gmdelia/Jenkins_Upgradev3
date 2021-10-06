FROM tomcat:8.0
RUN ls -al
#ADD **/*.war /usr/local/tomcat/webapps/
COPY ["../java-tomcat-sample/target/java-tomcat-maven-example.war", "/usr/local/tomcat/webapps/"]
EXPOSE 8080
CMD ["catalina.sh", "run"]
