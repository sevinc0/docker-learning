# Dockerfile

## Purpose

Create a custom Docker image using Dockerfile.

## Files

- Dockerfile
- index.html

## Commands

```bash
docker build -t mywebsite .
docker run -d -p 8080:80 mywebsite
```

## What I Learned

- FROM
- COPY
- EXPOSE
- Build Docker images
