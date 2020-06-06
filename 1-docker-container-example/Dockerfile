FROM openjdk:11

WORKDIR /app

ADD target/1-docker-container-example-0.0.1-SNAPSHOT.jar /app/myapp.jar

EXPOSE 8080

CMD ["java", "-jar", "/app/myapp.jar"]

# reference : https://docs.docker.com/engine/reference/run/
# docker build --tag docker-container-example:1.0 .
# docker images
# docker container ls
# docker run docker-container-example:1.0
# docker run -d docker-container-example:1.0
# docker stop {containerId}
# docker run -d -p 9090:8080 docker-container-example:1.0
       ### OR ##
       #docker run -d --publish=9090:8080 docker-container-example:1.0

# docker exec -it {containerId} bash
# curl localhost:8080
# exit
