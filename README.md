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

Docker compose build
> docker-compose build
> docker-compose build --no-cache

List all the images
> docker images

Running the containers in detached mode
> docker-compose up -d

List the running containers
> docker-compose ps
> docker ps (to see all the running containers)

Stop and remove the containers
> docker-compose down

See the docker networks
> docker network ls

    '''
    NETWORK ID     NAME                 DRIVER    SCOPE
    d35eb70e8096   bridge               bridge    local
    1d824b8c14b0   docker-all_default   bridge    local
    6b58989fc34c   host                 host      local
    dba3cdb7e771   mongo-network        bridge    local
    10e878330f7c   nginx_default        bridge    local
    ca7f87192934   none                 null      local
    '''