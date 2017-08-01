## kuromoji-server

### usage

1. $ docker pull daxanya/kuromoji-server-alpine
2. $ docker run -d -p 8080:8080 daxanya/kuromoji-server-alpine
3. access -> http://localhost:8080/kuromoji/


### include
+ kuromoji-server (ref: https://github.com/atilika/kuromoji-server)
+ openjdk8 (ref: https://github.com/docker-library/openjdk/blob/master/8-jdk/alpine/Dockerfile)
+ maven (ref: https://github.com/Zenika/alpine-maven/blob/master/jdk-8/Dockerfile)
+ jetty (ref: https://github.com/appropriate/docker-jetty/blob/cafead33ad5c46a0226bff9713719579828ace15/9.3-jre8/alpine/Dockerfile)

