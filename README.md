# mydockerfiles

## Intro
I'll use this repo to add the Dockerfiles and docker-compose that I've experimenting with. 

### How to use
Clone the repo or download the file and rename the file form Dockerfile__something_ to Docker file
Then just run the normal docker build

* e.g: docker build -t heatman_thin:v1 .

### Dockefiles:
* Docker_heatman - sill experimental to be used with Heatman by https://github.com/nagius/heatman

### DockerCompose:
* docker_compose_lemp.yml - A Docker compose file to start a HAProxy+Ngnix+Php+MariaDB got the reference from: https://mercurenews.com/en/lemp-stack-in-90-seconds-with-docker/


### TODO
* Find a way to get heatman working fine