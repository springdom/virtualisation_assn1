FROM ubuntu:14.04
MAINTAINER Matthew Taylor <taylomj5@student.op.ac.nz>
ENV REFRESHED_AT 2014-06-01

RUN apt-get -yqq update

VOLUME ["/data/","/var/www/html"]
WORKDIR /data

ENTRYPOINT ["/var/www/html"]

