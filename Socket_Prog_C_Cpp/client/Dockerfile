FROM ubuntu:latest
FROM gcc:latest

COPY . /usr/src/client

WORKDIR /usr/src/client

RUN gcc -o client client.c
