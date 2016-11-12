# docker-hello

Simple Docker image to say Hello World!

Build the image:
```
docker run -t pascalgrimaud/hello .
```

Or pull the image:
```
docker pull pascalgrimaud/hello
```

Then, run the image:
```
docker run --rm -it -p 8080:80 pascalgrimaud/hello
```
