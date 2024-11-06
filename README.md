# Ha1fdan's Docker Compose files

## Caddy

1. `docker network create proxy`
2. Edit/create `.env` file
3. Open port 80 and 443 in your firewall
4. `docker compose up -d`

## Portainer Agent

1. Open port 9001 in your firewall
2. `docker compose up -d`

## vlmcsd

1. Open port 1688 in your firewall
2. `docker compose up -d`


## Watchtower

1. `docker compose up -d`