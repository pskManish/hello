FROM tomcat:8.0-alpine

LABEL maintainer="manishtest"

ADD target/Myweb.war /usr/local/tomcat/webapps/

EXPOSE 8081

CMD ["catalina.sh", "run"]