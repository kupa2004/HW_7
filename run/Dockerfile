FROM tomcat:latest
WORKDIR /tmp
ADD hello-1.0.war /usr/local/tomcat/webapps
ENTRYPOINT ["catalina.sh", "jpda", "run"]
