FROM tomcat:latest
WORKDIR /tmp
RUN cp tmp/hello-1.0.war /usr/local/tomcat/webapps
ENTRYPOINT ["catalina.sh", "jpda", "run"]
