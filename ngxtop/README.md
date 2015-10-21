# ngxtop

This Dockerfile generates a minimalistic ngxtop image that is based on python:2-slim base image.

## Usage

To use this image, it is required to mount the logfile into the container.

```
docker run -t --rm -v <logfile>:/var/log/nginx/access.log:ro mishunika/ngxtop
```
