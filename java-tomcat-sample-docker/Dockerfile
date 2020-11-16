FROM tomcat:8.0
ADD java-tomcat-sample-docker/target/dependency/webapp-runner.jar /usr/local/tomcat/
EXPOSE 8080
CMD ["catalina.sh", "run"]
