FROM tomcat:9

 
RUN rm -rf /usr/local/tomcat/webapps/*

 
COPY /root/.jenkins/workspace/qa-pipeline/quality-assurence/warstorage /usr/local/tomcat/webapps/ROOT.war

 
EXPOSE 8080

 
CMD ["catalina.sh", "run"]
