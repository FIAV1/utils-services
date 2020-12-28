# Utils Services

Collection of Docker Compose utils services

## PostgreSQL

Spin up a PostgreSQL database with Adminer on port 8080

```bash
# Enter postgresql directory
cd postgresql

# Start PostgreSQL and Adminer
docker-compose -f "postgresql/docker-compose.yaml" up -d --build

# Stop PostgreSQL and Adminer
docker-compose -f "postgresql/docker-compose.yaml" down

# Stop PostgreSQL and Adminer and remove persistent volumes
docker-compose -f "postgresql/docker-compose.yaml" down --volumes
```
