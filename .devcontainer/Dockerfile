FROM node:20.18.1-bullseye AS dev

WORKDIR /app

RUN apt-get update && apt-get install -y docker.io

ARG USERNAME=node
ARG USER_UID=1000
ARG USER_GID=$USER_UID

RUN apt-get install -y sudo \
    && echo $
