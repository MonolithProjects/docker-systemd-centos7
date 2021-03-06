# CentOS7 Ansible Test Image

<a href="https://github.com/MonolithProjects/docker-systemd-centos7/actions"><img src="https://github.com/MonolithProjects/docker-systemd-centos7/workflows/Dockerfile%20test/badge.svg?branch=master"/></a>
<a href="https://hub.docker.com/repository/docker/monolithprojects/systemd-centos7"><img src="https://img.shields.io/microbadger/layers/monolithprojects/systemd-centos7"/></a>
<a href="https://hub.docker.com/repository/docker/monolithprojects/systemd-centos7"><img src="https://img.shields.io/docker/pulls/monolithprojects/systemd-centos7"/></a>
<a href="https://hub.docker.com/repository/docker/monolithprojects/systemd-centos7"><img src="https://img.shields.io/docker/cloud/automated/monolithprojects/systemd-centos7?maxAge=2592000"/></a>

Docker image with centos7 and enabled systemd. Image is updated with the latest software updates on the 1st day in the month. Image contains also `ansible` user (UID/GID 1000) with NOPASSWD:ALL sudo rights.  

**Note:** This docker image is ment to be used for Molecule Ansible tests and development purpose. I do not recomend to use it in production.

## Tags

- `latest`  
- `<monthly build timestamp>` for the list of the tags see the [Docker Hub](https://hub.docker.com/repository/docker/monolithprojects/systemd-centos7/tags?page=1)


## How-to

  1. Run command `docker pull monolithprojects/systemd-centos7:<tag>`  
  2. Run a container from the image: `docker run --detach --privileged --volume=/sys/fs/cgroup:/sys/fs/cgroup:ro monolithprojects/systemd-centos7:latest`  

## License

MIT
