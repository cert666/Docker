FROM ubuntu:latest
FROM gcc:latest

#EXPOSE 8080

COPY . usr/src/socket/server

WORKDIR usr/src/socket/server

#run -d --name web1 --net=host jonlangemak/docker:webinstance1

RUN gcc -o server server.c


#CMD ["./server"]
