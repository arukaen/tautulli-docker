## PlexPy Dockerfile

[![Build Status](https://travis-ci.org/arukaen/plexpy-docker.svg?branch=master)](https://travis-ci.org/arukaen/plexpy-docker)
[![](https://images.microbadger.com/badges/image/arukaen/plexpy.svg)](https://microbadger.com/images/arukaen/plexpy "Get your own image badge on microbadger.com")

This repository contains **Dockerfile** of [PlexPy](https://github.com/drzoidberg33/plexpy) for [Docker](https://www.docker.com/)'s [automated build](https://registry.hub.docker.com/u/arukaen/plexpy/) published to the public [Docker Hub](https://hub.docker.com/).

### What is Plexpy?
A python based web application for monitoring, analytics and notifications for [Plex Media Server](https://plex.tv).

### Base Docker Image

* [library/alpine:latest](https://github.com/docker-library/repo-info/blob/master/repos/alpine/tag-details.md#alpinelatest)

### Installation

1. Install [Docker](https://www.docker.com/).

2. `docker pull arukaen/plexpy`
    (You can also build the image from the Dockerfile: `docker build -t="arukaen/plexpy" github.com/arukaen/plexpy-docker`)

### Usage

#### Run `plexpy-docker`
    docker run --restart=always -d --name PlexPy -p 8181:8181 arukaen/plexpy
