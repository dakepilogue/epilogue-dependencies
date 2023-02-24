FROM dakepilogue/maven:3.6.3-jdk-8-slim

MAINTAINER zmz8323802@163.com
# Step : package jar
WORKDIR /app
COPY ./pom.xml ./

# Step : deploy jar
RUN mvn clean deploy -DskipTests