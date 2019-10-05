FROM openjdk:8-jre

ARG JAR_FILE
ADD target/${JAR_FILE} /opt/maven-docker/hello-world.jar

ENTRYPOINT ["java", "-jar", "/opt/maven-docker/hello-world.jar"]