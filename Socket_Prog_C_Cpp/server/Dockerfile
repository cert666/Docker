FROM ubuntu:latest
FROM gcc:latest


COPY . usr/src/socket/server

WORKDIR usr/src/socket/server

RUN gcc -o server server.c

