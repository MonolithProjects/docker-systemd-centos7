# CentOS7 Ansible Test Image

<a href="https://hub.docker.com/repository/docker/monolithprojects/systemd-centos7"><img src="https://img.shields.io/docker/automated/monolitprojects/systemd-centos7?logo=docker&logoColor=white"/>
<a href="https://hub.docker.com/repository/docker/monolithprojects/systemd-centos7"><img src="https://img.shields.io/docker/pulls/monolithprojects/systemd-centos7?logo=docker&logoColor=white"/>
<a href="https://github.com/MonolithProjects/docker-systemd-centos7/actions"><img src="https://github.com/MonolithProjects/docker-systemd-centos7/workflows/Build%20and%20Push/badge.svg?branch=master"/></a>

CentOS7 docker image (based on actual base image version). I am using it with Molecule for Ansible role testing.

## Tags

  - `latest`: Latest version of Ansible ready image


## How-to

  1. Run command `docker pull monolithprojects/systemd-centos7:latest`  
  2. Run a container from the image: `docker run --detach --privileged --volume=/sys/fs/cgroup:/sys/fs/cgroup:ro monolithprojects/systemd-centos7:latest`  

## License

MIT
