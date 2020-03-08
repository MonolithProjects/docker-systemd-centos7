# CentOS7 Ansible Test Image

<a href="https://github.com/MonolithProjects/docker-systemd-centos7/actions"><img src="https://github.com/MonolithProjects/docker-systemd-centos7/workflows/Dockerfile%20test/badge.svg?branch=master"/></a>
<a href="https://hub.docker.com/repository/docker/monolithprojects/systemd-centos7"><img src="https://img.shields.io/microbadger/layers/monolithprojects/systemd-centos7"/></a>
<a href="https://hub.docker.com/repository/docker/monolithprojects/systemd-centos7"><img src="https://img.shields.io/docker/pulls/monolithprojects/systemd-centos7"/></a>
<a href="https://hub.docker.com/repository/docker/monolithprojects/systemd-centos7"><img src="https://img.shields.io/docker/cloud/automated/monolithprojects/systemd-centos7?maxAge=2592000"/></a>

CentOS7 docker image with enabled systemd. I am using it with Molecule for Ansible role testing.

## Tags

  - `latest`: Latest version of the image
  - `7.7.1908`: CentOS 7.7.1908
  - `7.6.1810`: CentOS 7.6.1810


## How-to

  1. Run command `docker pull monolithprojects/systemd-centos7:<tag>`  
  2. Run a container from the image: `docker run --detach --privileged --volume=/sys/fs/cgroup:/sys/fs/cgroup:ro monolithprojects/systemd-centos7:latest`  

## License

MIT
