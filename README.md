# Ansible-Docker

This repository contains Ansible image of different OS.

Alpine OS
-------

`docker run -d --name ansible-alpine --restart always plaulkar/ansible:alpine`

Exec into the container

`docker exec -it ansible-alpine sh`


CentOS OS
-------

`docker run -d --name ansible-centos --restart always plaulkar/ansible:centos`

Exec into the container

`docker exec -it ansible-centos bash`


Ubuntu OS
-------

`docker run -d --name ansible-ubuntu --restart always plaulkar/ansible:ubuntu`

Exec into the container

`docker exec -it ansible-ubuntu bash`
