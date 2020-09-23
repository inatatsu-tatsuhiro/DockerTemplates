FROM golang:1.14-alpine
ENV GO111MODULE=on
RUN apk add git \
 && go get -u github.com/pilu/fresh 
CMD fresh