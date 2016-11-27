# hello

[![Circle CI](https://circleci.com/gh/pascalgrimaud/hello.svg?style=shield)](https://circleci.com/gh/pascalgrimaud/hello)[![Docker Build](https://img.shields.io/docker/automated/pascalgrimaud/hello.svg)](https://img.shields.io/docker/automated/pascalgrimaud/hello.svg)

Simple Docker image to say Hello World!

Pull the image: `docker pull pascalgrimaud/hello`

Or, you can build the image: `docker build -t pascalgrimaud/hello .`

Run the image directly: `docker run --rm -it -p 8080:80 pascalgrimaud/hello`

Run the image with docker-compose: `docker-compose up -d`

Then, go to: [http://localhost:8080](http://localhost:8080)
