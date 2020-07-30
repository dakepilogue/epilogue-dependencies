FROM harbor.emotibot.com/bfop/emotibot-maven-deploy:3-jdk-8

MAINTAINER mengzhenzhang@emotibot.com
# Step : package jar
WORKDIR /app
COPY ./ ./

# Step : deploy jar
RUN mvn clean deploy -DskipTests