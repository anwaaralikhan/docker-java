FROM java:8
WORKDIR /
VOLUME /tmp
EXPOSE 8080
ADD build/libs/docker-gradle-transmode-dockerfile-with-plugin-1.0.jar docker-gradle-transmode-dockerfile-with-plugin-1.0.jar
ENTRYPOINT ["java","-jar", "docker-gradle-transmode-dockerfile-with-plugin-1.0.jar" ]