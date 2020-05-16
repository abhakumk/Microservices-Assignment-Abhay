FROM fabric8/java-alpine-openjdk8-jdk
ADD target/*.jar eurekaserver.jar
RUN touch /eurekaserver.jar
EXPOSE 8761
ENTRYPOINT ["java","-jar","/eurekaserver.jar"]