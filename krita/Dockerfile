FROM ubuntu:latest
MAINTAINER Cristobal Silva <crsilva@ing.uchile.cl>

RUN apt-get update && \
    apt-get install -y software-properties-common

RUN add-apt-repository ppa:dimula73/krita -y && \
    apt-get update && \
    apt-get install -y krita3-testing && \
    apt-get purge -y software-properties-common

CMD ["krita"]
