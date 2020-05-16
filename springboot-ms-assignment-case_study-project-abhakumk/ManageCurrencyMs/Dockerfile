FROM fabric8/java-alpine-openjdk8-jdk
ADD target/*.jar managecurrms.jar
RUN touch /managecurrms.jar
ENTRYPOINT ["java","-jar","/managecurrms.jar"]