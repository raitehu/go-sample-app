# go version
FROM golang:1.16.3-alpine

# update apk & install git
RUN apk add --update
RUN apk add git

RUN mkdir /go/src/app
WORKDIR /go/src/app

ADD . /go/src/app
