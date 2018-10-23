[![Docker Automated build](https://img.shields.io/docker/automated/madeinoz/fedora-molecule.svg)](https://img.shields.io/docker/automated/madeinoz/fedora-molecule.svg)

# Dockerfiles for CI systems

| System | Version | Docker Pulls  |
| ------ | ------- | ------------- |
| Fedora | latest (27) | [![Docker Pulls](https://img.shields.io/docker/pulls/madeinoz/fedora-molecule.svg)](https://hub.docker.com/r/madeinoz/fedora-molecule) |
| CentOS | 7 | [![Docker Pulls](https://img.shields.io/docker/pulls/madeinoz/centos-molecule.svg)](https://hub.docker.com/r/madeinoz/centos-molecule) |
| Ubuntu | 16.04 & 18.04 | [![Docker Pulls](https://img.shields.io/docker/pulls/madeinoz/ubuntu-molecule.svg)](https://hub.docker.com/r/madeinoz/ubuntu-molecule) |
| OpenSUSE | Leap 15.0 | [![Docker Pulls](https://img.shields.io/docker/pulls/madeinoz/opensuse-molecule.svg)](https://hub.docker.com/r/madeinoz/opensuse-molecule) |
| Clear Linux | latest | [![Docker Pulls](https://img.shields.io/docker/pulls/madeinoz/clearlinux-molecule.svg)](https://hub.docker.com/r/madeinoz/clearlinux-molecule) |

These containers are based on https://github.com/paulfantom/dockerfiles by Pawel Krupa (@paulfantom)

Repository contains docker images for [molecule](https://github.com/metacloud/molecule) testing framework. Those images aren't supposed to run anywhere outside CI pipeline.
Every image comes with packages:
- python2
- iproute (iproute2 on Ubuntu 18.04)
- net-tools
- ca-certificates (Ubuntu and Debian)
- libcap2-bin (Ubuntu and Debian)

Images in [systemd](systemd) directory come with systemd installed.
