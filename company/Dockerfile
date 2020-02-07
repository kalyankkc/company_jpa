FROM tomcat:9.0
RUN echo 'Deploying War on Server'
RUN rm -rf /usr/local/tomcat/webapps/*
COPY target/demoapp-0.0.1-SNAPSHOT.jar /usr/local/tomcat/webapps/ROOT.jar
EXPOSE 8080
CMD ["catalina.sh", "run"]
