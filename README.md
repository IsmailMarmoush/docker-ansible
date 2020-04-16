# Docker Ansible Image

[![Docker Build Status](https://github.com/IsmailMarmoush/ansible-docker/workflows/Docker/badge.svg)](https://github.com/IsmailMarmoush/ansible-docker/actions?query=workflow%3ADocker)
[![Docker Pulls Status](https://img.shields.io/docker/pulls/ismailmarmoush/ansible-docker.svg)](https://hub.docker.com/r/ismailmarmoush/ansible-docker/)

## Run without any helper scripts
```
docker run -it ismailmarmoush/ansible-docker bash
docker run -it ismailmarmoush/ansible-docker <any other command>
```

## Run with helper script
```bash
# Default of ssh_dir is  ~/.ssh
# Default of network is nothing usually when you're talking to remote hosts not on your machine
./main.sh run ssh_dir=./myspecial_ssh
./main.sh run network=private_network
```

## Note
> quick-ansible.sh was removed for simplicity reasons
