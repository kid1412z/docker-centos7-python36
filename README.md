# docker-centos7-python36
Docker base image using CentOS 7 and Python3.6.0. The repositories of yum and pip are switched to the mirror of Aliyun for speeding up the installation process in China.

# Usage
## Build image

```
docker build -t kid1412z/centos7-python36
```

## Run container

```
docker run -it kid1412z/centos7-python36 /bin/bash
```

## Pulling prebuild image

```
docker pull kid1412z/docker-centos7-python36
```