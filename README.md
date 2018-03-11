## Tautulli Dockerfile
[![](https://images.microbadger.com/badges/image/arukaen/tautulli.svg)](https://microbadger.com/images/arukaen/tautulli "Get your own image badge on microbadger.com")

This repository contains **Dockerfile** of [Tautulli](https://github.com/Tautulli/Tautulli) for [Docker](https://www.docker.com/)'s [automated build](https://registry.hub.docker.com/u/arukaen/tautulli/) published to the public [Docker Hub](https://hub.docker.com/).

### What is Tautulli (formerly Plexpy)?
A python based web application for monitoring, analytics and notifications for [Plex Media Server](https://plex.tv).

### Base Docker Image

* [library/alpine:latest](https://github.com/docker-library/repo-info/blob/master/repos/alpine/tag-details.md#alpinelatest)

### Installation

1. Install [Docker](https://www.docker.com/).

2. `docker pull arukaen/tautulli`
    (You can also build the image from the Dockerfile: `docker build -t="arukaen/tautulli" github.com/arukaen/tautulli-docker`)

### Usage

#### Run `tautulli-docker`
    docker run --restart=always -d --name Tautulli -p 8181:8181 arukaen/tautulli
