FROM ubuntu:latest
MAINTAINER Cristobal Silva <crsilva@ing.uchile.cl>

RUN apt-get update && \
    apt-get install -y hdfview && \
    rm -rf /var/lib/apt/lists/*

CMD ["/usr/bin/hdfview"]
