Docker images with Ansible installed
====================================

[Official Docker images with Ansible installed](https://github.com/ansible/ansible-docker-base) are unfortunately deprecated.

This git repository is actively used to build images for several distributions and version.

You can find build images from this Dockerfile on [DockerHub](https://hub.docker.com/u/deimosfr/).

Build image
===========

To Build an image, enter in the desired folder and run a Docker build like that:
```
git clone https://github.com/deimosfr/docker-images-ansible.git
cd docker-images-ansible/debian-7
docker build --no-cache=true -t deimosfr/ansible-debian-7 .
```

Run image
=========

If you want to run pre built image:
```
docker pull deimosfr/ansible-debian-7
```
