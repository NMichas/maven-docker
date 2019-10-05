FROM openjdk:8-jre

ADD target/${project.build.finalName}-jar-with-dependencies.jar /opt/maven-docker/hello-world.jar

ENTRYPOINT ["java", "-jar", "/opt/maven-docker/hello-world.jar"]