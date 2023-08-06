# Laravel-app
Laravel-app with nginx and mysql in docker


# Intial Requirements:

- linux server (with docker engine and compose)


# Guide Line


1. Create your project Path
2. Write Docker-Compose yml and Dockerfile

# Docker Compose YML file:
This file is to build up the containers with images and the volumes with docker networks

# Dockerfile:
This docker file is to pre run or install the requirements applications or dependencies in the container before the container is run.


# Docker Commands:

1. docker compose up -d : to run the compose file and make the listed services run as the container
2. docker ps : to check the current live/running containers , it shows image id, ports map, container Id, container name
3. docker compose down: to stop and remove the running containners
4. docker stop/start <containerID> : to stop the specific container 

