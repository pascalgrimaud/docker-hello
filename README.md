# hello

[![Circle CI](https://circleci.com/gh/pascalgrimaud/hello.svg?style=shield)](https://circleci.com/gh/pascalgrimaud/hello)
[![Docker Build](https://img.shields.io/docker/automated/pascalgrimaud/hello.svg)](https://img.shields.io/docker/automated/pascalgrimaud/hello.svg)

Simple Docker image to say Hello World!

Docker image: https://hub.docker.com/r/pascalgrimaud/hello/

Build the image: `docker run -t pascalgrimaud/hello .`

Or pull the image: `docker pull pascalgrimaud/hello`

Then, run the image: `docker run --rm -it -p 8080:80 pascalgrimaud/hello`
