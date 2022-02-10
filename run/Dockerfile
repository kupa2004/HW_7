FROM tomcat:latest
RUN apt-get install default-jdk -y default-jdk
WORKDIR /home/HW_7/run
ADD hello-1.0.war /usr/local/tomcat/webapps
ENTRYPOINT ["catalina.sh", "jpda", "run"]
