FROM alpine

MAINTAINER cseabass <cseabass@student.21-school.ru>

RUN apk update && \
    apk upgrade && \
    apk add vim

ENTRYPOINT vim test

# Building
# docker build -t ex00 .

# Running
# docker run --rm -ti ex00
