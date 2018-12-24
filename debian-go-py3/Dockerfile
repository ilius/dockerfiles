FROM debian:testing

RUN apt-get update
RUN apt-get install -y golang-go bash python3

ENV GOPATH /opt/go

RUN go version
RUN python3 --version
