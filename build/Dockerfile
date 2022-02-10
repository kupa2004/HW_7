FROM maven:3.6.1-jdk-8 as build
RUN apt-get update
RUN apt-get install -y git
RUN rm -rf /var/lib/apt/lists/*
WORKDIR /home
RUN git clone https://github.com/boxfuse/boxfuse-sample-java-war-hello.git
WORKDIR boxfuse-sample-java-war-hello
RUN mvn package
WORKDIR target
RUN docker cp hello-1.0.war /home


