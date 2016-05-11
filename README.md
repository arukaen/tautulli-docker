## PlexPy Dockerfile

[![Build Status](https://travis-ci.org/arukaen/plexpy-docker.svg?branch=master)](https://travis-ci.org/arukaen/plexpy-docker)

This repository contains **Dockerfile** of [PlexPy](https://github.com/drzoidberg33/plexpy) for [Docker](https://www.docker.com/)'s [automated build](https://registry.hub.docker.com/u/arukaen/plexpy/) published to the public [Docker Hub](https://hub.docker.com/).

### Base Docker Image

* [library/alpine:latest](https://github.com/docker-library/docs/blob/master/alpine/tag-details.md#alpinelatest)

### Installation

1. Install [Docker](https://www.docker.com/).

2. `docker pull arukaen/plexpy`
    (You can also build the image from the Dockerfile: `docker build -t="arukaen/plexpy" github.com/arukaen/plexpy-docker`)

### Usage

#### Run `plexpy-docker`
    docker run -d --name PlexPy -p 8181:8181 arukaen/plexpy
