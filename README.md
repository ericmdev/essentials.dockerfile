## Dockerfile: Debian - Essentials

[![Build Status](https://travis-ci.org/ericmdev/essentials.dockerfile.svg?branch=master)](https://travis-ci.org/ericmdev/essentials.dockerfile)

**Dockerfile** of [Debian](https://www.debian.org/) essentials:

- nano

*Requirements*
- [Docker](https://www.docker.com/) 

*Base Docker Image*
- [debian:jessie](https://hub.docker.com/_/debian/)

*Docker Pull Command*
- `docker pull ericmdev/essentials`

### Usage

Build the image.

    $ make

Run the interactive container.

    $ make run

*See the `Makefile` for more options.