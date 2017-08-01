# docker-alpine

Minimal Docker image based on Alpine Linux

![](https://raw.githubusercontent.com/docker-library/docs/781049d54b1bd9b26d7e8ad384a92f7e0dcb0894/alpine/logo.png)

# Tags and links

*   [`3.4` (_versions/library-3.4/Dockerfile_)](https://github.com/rlesouef/docker-alpine/blob/master/3.4/Dockerfile)
*   [`3.5` (_versions/library-3.5/Dockerfile_)](https://github.com/rlesouef/docker-alpine/blob/master/3.5/Dockerfile)
*   [`3.6`, `latest` (_versions/library-3.6/Dockerfile_)](https://github.com/rlesouef/docker-alpine/blob/master/3.6/Dockerfile)

# Quick reference

*   **Where to get help**:  
    [the Docker Community Forums](https://forums.docker.com/), [the Docker Community Slack](https://blog.docker.com/2016/11/introducing-docker-community-directory-docker-community-slack/), or [Stack Overflow](https://stackoverflow.com/search?tab=newest&q=docker)

*   **Where to file issues**:  
    [https://github.com/rlesouef/docker-alpine/issues](https://github.com/rlesouef/docker-alpine/issues)

*   **Maintained by**:  
    [o2s : Open Source Services](https://github.com/rlesouef/docker-alpine)

# How to use this image

## Usage

Use like you would any other base image:

    FROM alpine:3.5
    RUN apk add --no-cache mysql-client
    ENTRYPOINT ["mysql"]
