FROM tomcat:8.0
#ADD **/*.war /usr/local/tomcat/webapps/
COPY /usr/jenkins/workspace/build tomcat docker image/java-tomcat-sample/target/java-tomcat-maven-example.war /usr/local/tomcat/webapps/
EXPOSE 8080
CMD ["catalina.sh", "run"]
