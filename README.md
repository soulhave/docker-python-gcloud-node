# Python with Node env to run tests

Base image with:
- python 2.7.12
- node v8.4.0
- npm v5.0.3
- yarn 0.27.5
- chromedriver 2.31
- phantomjs 2.1.1

# Docker hub

[lukasborges/python-gcloud-node](https://hub.docker.com/r/lukasborges/python-gcloud-node/)

# Commands


## Build the image
```
docker build -t lukasborges/python-gcloud-node:v7 .
```

## Push the image

```
docker push lukasborges/python-gcloud-node:v7
```
