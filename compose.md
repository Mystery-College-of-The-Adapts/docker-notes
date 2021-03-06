# Compose

Create images and containers
```zsh
docker-compose up
```

Create images and container in detached mode
```zsh
docker-compose up -d
```

Stop and remove all containers and networks
```zsh
docker-compose down
```

Remove all volumes
```zsh
docker-compose down -v
```

Build images without creating containers
```zsh
docker-compose build
```

Run a single service from a `docker-compose.yml` file
```zsh
docker-compose run [SERVICE] [CMD]
```

Run a single service from a `docker-compose.yml` file and remove the container when it is stopped
```zsh
docker-compose run --rm [SERVICE] [CMD]
```

Force docker compose to rebuild images
```zsh
docker-compose up --build [SERVICE]
```
