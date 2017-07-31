# docker_kuromoji_server

## Make docker image

1. git clone https://github.com/atilika/kuromoji-server.git
2. docker build ./ -t alpine_kuromoji_server
3. docker run -d -p 8080:8080 alpine_kuromoji_server mvn jetty:run


## ref
+ https://github.com/docker-library/openjdk/blob/master/8-jdk/alpine/Dockerfile
+ https://hub.docker.com/r/markfletcher/graphviz/~/dockerfile/
+ https://hub.docker.com/r/vochicong/kuromoji-server/~/dockerfile/
+ https://github.com/Zenika/alpine-maven/blob/master/jdk-8/Dockerfile
+ https://github.com/appropriate/docker-jetty/blob/cafead33ad5c46a0226bff9713719579828ace15/9.3-jre8/alpine/Dockerfile

