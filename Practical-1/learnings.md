# Practical 1 – What I Learned

## Docker Fundamentals

- Docker is a platform used to build, run and manage containers.
- A Docker image is a template used to create containers.
- A Docker container is a running or stopped instance of an image.
- Docker Pull downloads an existing image.
- Docker Build creates a custom image using a Dockerfile.
- Docker Run creates and starts a container.

## Container Management

- `docker ps` displays running containers.
- `docker ps -a` displays all containers.
- `docker start` starts a stopped container.
- `docker stop` stops a running container.
- `docker rm` removes a container.
- `docker images` lists available images.

## Linux Commands Practised

- `whoami` – checks the current user.
- `pwd` – displays the current directory.
- `ls -la` – lists files and directories.
- `df -h` – checks disk usage.
- `free -h` – checks memory information.
- `ps aux` – displays running processes.
- `hostname` – displays the container hostname.
- `cat /etc/os-release` – displays OS information.

## Important Concepts

1. Containers can be started again after being stopped.
2. Removing a container does not automatically remove its image.
3. Each container has its own filesystem view and process environment.
4. The main process inside a container is PID 1.

## Practical Result

Successfully practised basic Docker image and container operations using an Ubuntu container on AWS EC2.
