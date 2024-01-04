#Start with a base image containing Java runtime
FROM openjdk:17-jdk-slim

#Information around who maintains the image
MAINTAINER jacyjay.com

# Add the application's jar to the image
COPY target/accounts-borrow-me-0.0.1-SNAPSHOT.jar accounts-borrow-me-0.0.1-SNAPSHOT.jar

# execute the application
ENTRYPOINT ["java", "-jar", "accounts-borrow-me-0.0.1-SNAPSHOT.jar"]