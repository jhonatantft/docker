# jsTools
[![MIT License](https://img.shields.io/github/license/mkenney/k8s-proxy.svg)](https://github.com/jhonatantft/docker/blob/master/LICENSE)
![stability-beta](https://img.shields.io/badge/stability-beta-33bbff.svg)

## Image
  #### [`debian`, `node-11.x` Dockerfile](https://github.com/jhonatantft/docker/blob/master/jstools/Dockerfile)
![stability-locked](https://img.shields.io/badge/stability-locked-4b0088.svg) Based on[`debian:latest`](https://hub.docker.com/_/debian)

## Features Available
 - Node (11.x)
 - npm
 - gulp-cli
 - grunt-cli
 - bower
 - eslit
 - webpack-cli

## Installation
Assuming that you already have Docker installed. You need to able to run docker commands without sudo.

## Getting started
- Build image
```
docker build -t "image_name" .
```
- Exec container
```
docker run -it "image_name"
```
