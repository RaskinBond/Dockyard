FROM tomcat:9.0.78-jdk8-temurin-jammy
ADD https://referenceapplicationskhaja.s3.us-west-2.amazonaws.com/gameoflife.war /usr/local/tomcat/webapps
EXPOSE 8080
CMD [ "java", "-jar", "gameoflife.war" ]