FROM fabric8/java-alpine-openjdk8-jdk
ADD target/*.jar convertcurrms.jar
RUN touch /convertcurrms.jar
EXPOSE 9002
ENTRYPOINT ["java","-jar","/convertcurrms.jar"]