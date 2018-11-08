FROM ubuntu:latest
RUN apt-get update
RUN apt-get install -y apache2
RUN apt-get update
RUN apt-get install -y tomcat8
COPY /CubeGeneratorWeb/target/*.war /var/lib/tomcat8/webapps/
