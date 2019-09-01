# blueocean-with-docker-compose
Dockerfile & docker-compose.yml for using jenkinsci/blueocean with docker-compose

The Dockerfile is used to build a new image that starts with jenkinsci/blueocean but adds a layer that ensures docker-compose is installed properly and available as an executable binary from Jenkins pipelines.

## Build custom image and start up your custom jenkinsci/blueocean container that includes docker-compose
```
docker-compose up -d
```
