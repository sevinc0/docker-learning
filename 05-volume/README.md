# Docker Volume

## Purpose

Share files between the host machine and the Docker container.

## Commands

```bash
docker run -d -p 8081:80 \
-v $(pwd)/html:/usr/share/nginx/html nginx
```

## What I Learned

- Bind Mount
- Docker Volume
- Data Persistence
