## Node.js w/ Bower & Gulp Dockerfile


This repository contains **Dockerfile** of [Node.js](http://nodejs.org/) w/ [Bower](http://bower.io/) & [Gulp](http://gulpjs.com/) for [Docker](https://www.docker.com/)'s [automated build](https://registry.hub.docker.com/u/dockerfile/nodejs-bower-gulp/) published to the public [Docker Hub Registry](https://registry.hub.docker.com/).


### Base Docker Image

* [dockerfile/nodejs](http://dockerfile.github.io/#/nodejs)


### Installation

1. Install [Docker](https://www.docker.com/).

2. Download [automated build](https://registry.hub.docker.com/u/dockerfile/nodejs-bower-gulp/) from public [Docker Hub Registry](https://registry.hub.docker.com/): `docker pull dockerfile/nodejs-bower-gulp`

   (alternatively, you can build an image from Dockerfile: `docker build -t="dockerfile/nodejs-bower-gulp" github.com/dockerfile/nodejs-bower-gulp`)


### Usage

    docker run -it --rm dockerfile/nodejs-bower-gulp

#### Run `node`

    docker run -it --rm dockerfile/nodejs-bower-gulp node

#### Run `npm`

    docker run -it --rm dockerfile/nodejs-bower-gulp npm

#### Run `bower`

    docker run -it --rm dockerfile/nodejs-bower-gulp bower

#### Run `gulp`

    docker run -it --rm dockerfile/nodejs-bower-gulp gulp
