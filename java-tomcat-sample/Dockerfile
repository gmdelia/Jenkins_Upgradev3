FROM tomcat-custom
RUN pwd
COPY ./**/*.war /usr/local/tomcat/webapps

EXPOSE 8080

CMD [ "catalina.sh" , "run" ]