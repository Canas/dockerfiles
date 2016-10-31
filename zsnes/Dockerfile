FROM debian:latest
MAINTAINER Cristobal Silva <crsilva@ing.uchile.cl>

RUN dpkg --add-architecture i386 && \
    apt-get update && \
    apt-get install -y zsnes && \
    rm -rf /var/lib/apt/lists/*

CMD ["/usr/bin/zsnes"]
