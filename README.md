# Simple Docker Web Application

## Introduction

- The example is copied from https://github.com/aiordache/demos/tree/master/dockercon2020-demo


## Some Useful Commands

- Connect to a bash terminal shell in a container
  - Command: ```docker container exec -it 4433bddb8b76 /bin/bash```
  - The -it parameters is the container ID


- list running containers: ```docker container ls```

- Start the environment in the docker-compose.yaml:
  - ```docker-compose up -d```
  - ```-d``` means "as daemons in the background" (detached)
