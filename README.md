# Docker Redis boilerplate 🐳

Docker container with Redis caching. Quickly add a caching layer to your database for local development.

## Steps

1. Install [Docker](https://docs.docker.com/desktop/setup/install/mac-install/)
2. Clone repository: `git clone https://github.com/silmu/docker-redis-boilerplate.git`
3. Run: `docker-compose up -d`

## Using Redis

### Logging into Redis

```sh
docker exec -it redis redis-cli
```

### Basic Commands

- **PING**: `PING`
- **Set key value pair**: `SET keyName yourValue`
- **Get value**: `GET keyName`
- **Delete key value pair**: `DEL keyName`
- **Get all keys**: `KEYS *`
- **Get key by a pattern**: `KEYS user:123:*`
- **Exit**: `Crtl + C`

For more, see the [Redis documentation](https://redis.io/docs/latest/commands/).
