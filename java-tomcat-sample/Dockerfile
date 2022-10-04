FROM tomcat-custom
RUN rm -R -f ROOT
COPY **/*.war /usr/local/tomcat/webapps/ROOT.war

EXPOSE 8080

CMD [ "catalina.sh" , "run" ]