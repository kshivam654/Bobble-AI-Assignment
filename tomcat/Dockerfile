FROM tomcat
MAINTAINER Shivam kshivam654@gmail.com
RUN apt update
RUN apt install telnet
RUN apt install net-tools
RUN apt install curl
RUN apt install vim -y
COPY sample.war /usr/local/tomcat/webapps
ENV role=app
ENV env=dev
ENV name=shivam
EXPOSE 9191
CMD ["/usr/local/tomcat/bin/catalina.sh", "run"]