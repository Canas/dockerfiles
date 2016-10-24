FROM ubuntu:latest
MAINTAINER Cristobal Silva <crsilva@ing.uchile.cl>

RUN dpkg --add-architecture i386 && \
    apt-get update && \
    apt-get install -y zsnes

CMD ["/usr/bin/zsnes"]
