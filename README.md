# Docker exercises

## Docker commands

> docker compose version 
or 
> docker-compose --version

> docker image ls -q 
Shows images id

Remove docker containers
> docker container rm -f $(docker container ls -aq)

Remove docker images
> docker image rm $(docker image ls -q)
