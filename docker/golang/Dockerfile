FROM golang:latest

RUN apt update -qq && \
    apt install -y mariadb-client-10.3 vim

WORKDIR /go/src/work

ENV GO111MODULE=on

ADD . .
<<<<<<< HEAD
=======

RUN go mod init


#RUN go get -u github.com/golang/dep/cmd/dep \
#              bitbucket.org/liamstask/goose/cmd/goose

#ADD . .

#RUN go get -u github.com/go-sql-driver/mysql
#RUN go get -u github.com/google/uuid
#RUN go get -u github.com/gorilla/mux
>>>>>>> 054c23d... [fix]Windows環境で動作していないことを修正
