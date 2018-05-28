# dockermc
If i would have a ****** clue what this will do, now that would be nice for a change

FROM ubuntu:16.04

MAINTAINER dockeresneved

RUN apt-get –y update \
&& apt-get –y upgrade \
&& apt-get –y install mc \
&& apt-get –y clean
WORKDIR /root
