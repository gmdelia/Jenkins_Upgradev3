FROM tomcat:8.0
#ADD **/*.war /usr/local/tomcat/webapps/
COPY ../java-tomcat-sample/target/*.war /usr/local/tomcat/webapps/
EXPOSE 8080
CMD ["catalina.sh", "run"]
