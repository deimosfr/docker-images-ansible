FROM ubuntu:16.04
MAINTAINER Pierre Mavro <pierre@mavro.fr>
# Install Ansible
RUN apt-get update
RUN apt-get install -y software-properties-common git
RUN apt-add-repository -y ppa:ansible/ansible
RUN apt-get update
RUN apt-get install -y ansible
RUN mkdir -p /etc/ansible/roles
# Install Ansible inventory file
RUN echo "[local]\nlocalhost ansible_connection=local" > /etc/ansible/hosts
