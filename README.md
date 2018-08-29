# jenkins-nginx

Jenkins up and running using nginx and docker

## Quickstart

clone the repository, go to the project's root and launch and type

```sh
docker-compose up -d
```
Get wait for the containers to start and jenkins will be available on http://localhost:8080

## How it works

It's a docker-compose project which has two services:

- jenkins (jenkinsci/blueocean): The jenkins master
- nginx (nginx): Reverse proxy to handle connections to the jenkins master
