FROM    tomcat:9.0.20-jre8-alpine
LABEL   maintainer="Rodrigo Santomauro"

EXPOSE  8080
RUN     rm -rf /usr/local/tomcat/webapps/docs/
RUN     rm -rf /usr/local/tomcat/webapps/manager/
RUN     rm -rf /usr/local/tomcat/webapps/host-manager/
RUN     rm -rf /usr/local/tomcat/webapps/examples/
ONBUILD COPY ROOT /usr/local/tomcat/webapps/ROOT/
ONBUILD ENTRYPOINT ["/usr/local/tomcat/bin/catalina.sh","run"]