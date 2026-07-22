# Run Docker Container

## Purpose

Learn how to run a Docker container using the official Nginx image.

## Commands

```bash
docker run -d -p 8080:80 --name nginx-container nginx
docker ps
docker stop nginx-container
docker rm nginx-container
```

## What I Learned

- Pull Docker images
- Run containers
- Stop containers
- Remove containers
- Port mapping
