FROM ubuntu:latest
FROM gcc:latest


EXPOSE 8080

COPY . /usr/src/client

WORKDIR /usr/src/client

#RUN -d --net=certnet
#run -d --name web1 --net=host

RUN gcc -o client client.c

#CMD ["./client"]