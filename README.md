# iQVoc Vocabulary Server

NDS Labs Docker image for the [iQVoc](https://github.com/innoq/iqvoc) vocabulary server.

## Prerequisites
* Docker

## Build
To build the image from the Dockerfile:
```bash
docker build -t ndslabs/iqvoc .
```

## Run the image
To run the Docker image:
```bash
docker run -it -p 3000:3000 ndslabs/iqvoc
```

The image will be pulled from [DockerHub](https://hub.docker.com/) if it does not already exist on your local machine.

## See also
* https://github.com/nds-org/ndslabs
* https://github.com/nds-org/ndslabs-specs
