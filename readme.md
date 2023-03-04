# Docker Cheatsheet 🐬

This is an ultimate cheatsheet for Docker users. It includes various commands and tips for managing Docker images, containers, logs, stats, networking, volumes, and more. Whether you're new to Docker or a seasoned pro, this cheatsheet is a must-have for your toolbox.

![docker image](https://imgur.com/9UqzhD8.png)

## Table of Contents

- [Docker Images](#docker-images)
- [Docker Containers](#docker-containers)
- [Docker Logs](#docker-logs)
- [Docker Stats](#docker-stats)
- [Docker Compose](#docker-compose)
- [Docker Registry](#docker-registry)
- [Docker Swarm](#docker-swarm)
- [Docker Networking](#docker-networking)
- [Docker Volumes](#docker-volumes)
- [Docker Miscellaneous](#docker-miscellaneous)

## Docker Images

| Title                     | Command                    |
| :------------------------ | :------------------------- |
| Search for Docker images: | docker search [image name] |
| Pull a Docker image:      | docker pull [image name]   |
| List Docker images:       | docker images              |
| Remove a Docker image:    | docker rmi [image ID]      |

## Docker Containers

| Title                                    | Command                                      |
| :--------------------------------------- | :------------------------------------------- |
| Run a Docker container:                  | docker run [options] [image name]            |
| List running Docker containers:          | docker ps                                    |
| List all Docker containers:              | docker ps -a                                 |
| Start a stopped Docker container:        | docker start [container name or ID]          |
| Stop a running Docker container:         | docker stop [container name or ID]           |
| Restart a Docker container:              | docker restart [container name or ID]        |
| Remove a Docker container:               | docker rm [container name or ID]             |
| Execute a command in a Docker container: | docker exec [container name or ID] [command] |

## Docker Logs

| Title                                           | Command                                       |
| :---------------------------------------------- | :-------------------------------------------- |
| Show Docker container logs:                     | docker logs [container name or ID]            |
| Follow Docker container logs:                   | docker logs -f [container name or ID]         |
| Show the last N lines of Docker container logs: | docker logs --tail [N] [container name or ID] |

## Docker Stats

| Title                                                         | Command                             |
| :------------------------------------------------------------ | :---------------------------------- |
| Show resource usage statistics for running Docker containers: | docker stats [container name or ID] |

## Docker Compose

| Title                 | Command             |
| :-------------------- | :------------------ |
| Start Docker Compose: | docker-compose up   |
| Stop Docker Compose:  | docker-compose down |

## Docker Registry

| Title                                | Command                       |
| :----------------------------------- | :---------------------------- |
| Login to a Docker registry:          | docker login [registry name]  |
| Logout from a Docker registry:       | docker logout [registry name] |
| Push a Docker image to a registry:   | docker push [image name]      |
| Pull a Docker image from a registry: | docker pull [image name]      |

## Docker Swarm

| Title                        | Command                                                                  |
| :--------------------------- | :----------------------------------------------------------------------- |
| Initialize a Docker swarm:   | docker swarm init                                                        |
| Join a Docker swarm:         | docker swarm join --token [token] [manager IP]:[port] --[worker/manager] |
| List Docker swarm nodes:     | docker node ls                                                           |
| Deploy a Docker service:     | docker service create [options] [image name]                             |
| List Docker services:        | docker service ls                                                        |
| Show Docker service logs:    | docker service logs [service name]                                       |
| Show Docker service tasks:   | docker service ps [service name]                                         |
| Show Docker service details: | docker service inspect [service name]                                    |
| Update a Docker service:     | docker service update [options] [service name]                           |
| Scale a Docker service:      | docker service scale [service name]=N                                    |
| Remove a Docker service:     | docker service rm [service name]                                         |

## Docker Networking

| Title                                         | Command                                                         |
| :-------------------------------------------- | :-------------------------------------------------------------- |
| Create a Docker network:                      | docker network create [network name]                            |
| List all Docker networks:                     | docker network ls                                               |
| Inspect a Docker network:                     | docker network inspect [network name]                           |
| Connect a Docker container to a network:      | docker network connect [network name] [container name or ID]    |
| Disconnect a Docker container from a network: | docker network disconnect [network name] [container name or ID] |

## Docker Volumes

| Title                                 | Command                                                   |
| :------------------------------------ | :-------------------------------------------------------- |
| Create a Docker volume:               | docker volume create [volume name]                        |
| List all Docker volumes:              | docker volume ls                                          |
| Inspect a Docker volume:              | docker volume inspect [volume name]                       |
| Remove a Docker volume:               | docker volume rm [volume name]                            |
| Mount a Docker volume to a container: | docker run -v [volume name]:[container path] [image name] |

## Docker Miscellaneous

| Title                            | Command                                                  |
| :------------------------------- | :------------------------------------------------------- |
| Show Docker version information: | docker version                                           |
| Show Docker system information:  | docker system info                                       |
| Show Docker disk usage:          | docker system df                                         |
| Build a Docker image:            | docker build [options] [directory containing Dockerfile] |
| Tag a Docker image:              | docker tag [image name] [new image name]:[tag]           |
| Rename a Docker image:           | docker tag [old name] [new name]                         |
| Remove unused Docker objects:    | docker system prune                                      |
| Inspect a Docker object:         | docker inspect [object name or ID]                       |

## Contributing

We welcome contributions to the Docker Cheat Sheet from anyone in the community. If you have any suggestions or improvements, please feel free to submit a pull request. Your contributions will help make this cheat sheet even more valuable for all Docker users.

## Acknowledgements 👏

We would like to thank all the contributors who have helped make this cheat sheet possible. Your hard work and dedication are greatly appreciated!
