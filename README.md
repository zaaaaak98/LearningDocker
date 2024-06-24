This is a repo for my docker lessons. As I work through docker lessons, I will upload my progress through GitHub.

Helpful docker commands :

- docker run : Will attempt to run a docker container. If the container is not found, it will attempt to download that container from docker hub.

- docker ps : shows any running containers

- docker ps -a : shows any containers that have been run previously, and shows how recently they were run

- docker images : shows any images that have been downloaded to local docker host from docker hub

- docker run <container ID> : runs specified container

- docker restart <container ID> : restarts specified container

- docker stop <container ID> : stops specified container

- docker logs <container ID> : shows any logs from the specified container

- docker rm <container ID> : deletes specified container

- docker rmi <image ID> : deletes specified image 