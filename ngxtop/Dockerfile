FROM python:2-slim

MAINTAINER Mihai Iachimovschi mihai.iachimovschi+docker@gmail.com

RUN apt-get -qq update && apt-get install -y \
    nginx && \
    apt-get clean && \
    rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*

RUN pip install ngxtop
ENTRYPOINT ["ngxtop"]
