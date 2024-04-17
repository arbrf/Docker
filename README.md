# Docker

docker container run -d -p 5000:5000 in28min/hello-world-nodejs:0.0.1.RELEASE
docker container run -d -p 5000:5000 in28min/hello-world-java:0.0.1.RELEASE
docker container run -d -p 5000:5000 in28min/hello-world-python:0.0.1.RELEASE
docker container ls 
docker image ls
docker container stop cc
docker container run -d -p 5001:5000 in28min/hello-world-nodejs:0.0.1.RELEASE
docker container run -d -p 5002:5000 in28min/hello-world-nodejs:0.0.1.RELEASE
docker container run -p 5003:5000 in28min/hello-world-nodejs:0.0.1.RELEASE
docker container run -p 5003:5000 in28min/hello-world-nodejs:0.0.1.RELEASE
 
docker --version
docker container ls
docker build -t in28min/hello-world-docker:v1 .
docker image list
docker run -d -p 5000:5000 in28min/hello-world-docker:v1
docker build -t in28min/hello-world-docker:v2 .
docker container run -d -p 5000:5000 in28min/hello-world-docker:v2
docker build -t in28min/hello-world-docker:v3 .
docker container run -d -p 5000:5000 in28min/hello-world-docker:v3
docker build -t in28min/hello-world-docker:v4 .


https://github.com/in28minutes/master-spring-and-spring-boot/tree/main/83-docker/hello-world-java
