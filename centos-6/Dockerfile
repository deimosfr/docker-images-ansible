FROM centos:centos6
MAINTAINER Pierre Mavro <pierre@mavro.fr>
RUN yum clean all && \
    yum -y install epel-release && \
    yum -y install python-pip python-devel gcc libffi-devel openssl-devel
RUN pip install ansible
RUN mkdir -p /etc/ansible/roles
RUN echo '[local]\nlocalhost\n' > /etc/ansible/hosts
