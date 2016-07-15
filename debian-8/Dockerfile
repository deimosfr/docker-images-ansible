FROM debian:jessie
MAINTAINER Pierre Mavro <pierre@mavro.fr>
RUN apt-get update && \
    apt-get -y install python-dev python-pip libffi-dev
RUN pip install ansible
RUN mkdir -p /etc/ansible/roles
RUN echo '[local]\nlocalhost\n' > /etc/ansible/hosts
