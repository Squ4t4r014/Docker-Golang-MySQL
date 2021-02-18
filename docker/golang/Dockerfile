FROM golang:latest

RUN apt update -qq && \
    apt install -y mariadb-client-10.3 vim

WORKDIR /go/src/work

ENV GO111MODULE=on

ADD . .
