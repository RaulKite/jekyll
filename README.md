# Dockerized Jekyll

This is a Dockerfile for a Jekyll Blog

The image is available from [Docker Hub](https://registry.hub.docker.com/u/raulkite/jekyll/).

## Usage:

```
docker -d run -v $PWD/blog:/blog -p 80:4000 raulkite/jekyll
```
