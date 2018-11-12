# Parse Server Dashboard - Docker Compose Setup

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

Parse server and Parse dashboard setup through docker compose, helps complete  installation in minutes and start project.

  - Works well with Windows volume mounting
  - All in on docker + compose setup
  - No additional setup work required

### Tech

This project uses open source projects to work properly:

* [Parse Server](https://parseplatform.org/) - Parse Server!
* [MongoDB](https://www.mongodb.com/) - MongoDB
* [Docker](https://www.docker.com/) - Docker
* [Docker Compose](https://docs.docker.com/compose/overview/) - Docker comopose a tool for docker

### Installation

This project requires [Docker Community Edition](https://www.docker.com/) 18+ to run.

Start the server.

```sh
$ nano docker-compose.yml -- (edit appId, masterKey, user and pass with yours)
$ cd parse-docker-dasboard
$ mkdir mongodbdata
$ docker-compose up -d
```

License
----
GPL
