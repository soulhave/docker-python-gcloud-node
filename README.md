# Python with Node env to run tests

Base image with:
- python 2.7.14
- node v8.9.4
- npm v5.7.1
- yarn 1.6.0
- chromedriver 2.31
- phantomjs 2.1.1

# Docker hub

[ciandt/docker-python-gcloud-node](https://hub.docker.com/r/ciandt/docker-python-gcloud-node/)

# Commands


## Build the image
```
docker build -t ciandt/docker-python-gcloud-node:[vN] .
```

## Push the image

```
docker push ciandt/docker-python-gcloud-node:[vN]
```

## Test local

```
docker run -it --volume=/Users/mendesdesouza/google-requisition-form:/localDebugRepo --workdir="/localDebugRepo" --memory=4g --memory-swap=4g --memory-swappiness=0 --entrypoint=/bin/bash ciandt/docker-python-gcloud-node
```

vN -> Is the docker version
