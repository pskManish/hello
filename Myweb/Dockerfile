FROM tomcat:8.0-alpine
RUN sed -i 's/port="8080"/port="8081"/' ${CATALINA_HOME}/conf/server.xml
LABEL maintainer="manishtest"

ADD Myweb/target/Myweb.war /usr/local/tomcat/webapps/

EXPOSE 8081:8081

CMD ["catalina.sh", "run"]