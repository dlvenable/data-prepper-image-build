FROM gradle:jdk11

COPY data-prepper /home/gradle/project
WORKDIR /home/gradle/project

RUN gradle --parallel clean assemble
