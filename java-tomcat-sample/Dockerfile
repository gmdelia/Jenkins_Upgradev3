FROM tomcat-custom
RUN pwd
COPY **/*.war /usr/local/tomcat/webapps

EXPOSE 8081

CMD [ "catalina.sh" , "run" ]