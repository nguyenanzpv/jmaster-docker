#base image; linux os alpine with open jdk 8
FROM eclipse-temurin:8-jre-alpine
#copy from jar local to docker image
#copy vao thu muc goc cua project
COPY target/accountService-0.0.1-SNAPSHOT.jar accountService-0.0.1-SNAPSHOT.jar
#command line to run jar
ENTRYPOINT ["java","--jar","/accountService-0.0.1-SNAPSHOT.jar"]