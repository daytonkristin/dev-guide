# Docker Cheatsheet

## Docker Commands
- `docker --version`: Show the Docker version.
- `docker info`: Display system-wide information about Docker.
- `docker help`: Get a list of available commands.

## Container Management
- `docker ps`: List running containers.
- `docker ps -a`: List all containers (running and stopped).
- `docker start <container_id>`: Start a stopped container.
- `docker stop <container_id>`: Stop a running container.
- `docker rm <container_id>`: Remove a stopped container.
- `docker exec -it <container_id> <command>`: Execute a command in a running container.

## Image Building
- `docker build -t <image_name>:<tag> .`: Build an image from a Dockerfile in the current directory.
- `docker images`: List all images.
- `docker rmi <image_id>`: Remove an image.
- `docker pull <image_name>`: Download an image from Docker Hub.

## Networking
- `docker network ls`: List all networks.
- `docker network create <network_name>`: Create a new network.
- `docker network connect <network_name> <container_id>`: Connect a container to a network.
- `docker network disconnect <network_name> <container_id>`: Disconnect a container from a network.

## Useful Links
- [Docker Documentation](https://docs.docker.com/) - Comprehensive Docker documentation.

> **Note:** Replace `<container_id>`, `<image_name>`, `<tag>`, and `<network_name>` with actual values as needed.