FROM ubuntu:16.04

LABEL maintainer="Sagar Patke <https://github.com/sagarpatkeatl>"
LABEL organization="StackRoute <http://stackroute.in>,<https://github.com/stackroute-io>"

RUN apt-key adv --keyserver keyserver.ubuntu.com --recv-keys 7BB9C367 && \
    echo "deb http://ppa.launchpad.net/ansible/ansible/ubuntu xenial main" | tee - /etc/apt/sources.list.d/ansible.list && \
    apt update && \
    apt install -y git ansible && \
    rm -rf /var/lib/apt/lists/*
