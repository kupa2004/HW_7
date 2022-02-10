FROM tomcat:latest
RUN apt-get install default-jdk -y default-jdk
WORKDIR /tmp
ADD hello-1.0.war /usr/local/tomcat/webapps
ENTRYPOINT ["catalina.sh", "jpda", "run"]
