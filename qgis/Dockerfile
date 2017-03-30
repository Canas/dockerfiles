FROM ubuntu:latest
MAINTAINER Cristobal Silva <crsilva@ing.uchile.cl>

RUN printf "deb http://qgis.org/debian xenial main\ndeb-src http://qgis.org/debian xenial main\n" >> /etc/apt/sources.list && \
    apt-key adv --keyserver keyserver.ubuntu.com --recv-key 073D307A618E5811

RUN apt-get update && \
    apt-get install -y qgis python-qgis qgis-plugin-grass && \
    rm -rf /var/lib/apt/lists/*

CMD ["/usr/bin/qgis"]
