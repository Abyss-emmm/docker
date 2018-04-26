#Ubuntu-i386
#VERSION    1
FROM i386/ubuntu:16.04
MAINTAINER Abyss

RUN mv /etc/apt/sources.list /etc/apt/sources.list.backup
ADD sources.list /etc/apt/sources.list
RUN apt-get update && apt-get install -y build-essential vim
