FROM java:8
WORKDIR /
VOLUME /tmp
EXPOSE 8080
ADD build/libs/docker-gradle-transmode-dockerfile-with-plugin-0.0.1-SNAPSHOT.jar docker-gradle-transmode-dockerfile-with-plugin-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java","-jar", "docker-gradle-transmode-dockerfile-with-plugin-0.0.1-SNAPSHOT.jar" ]