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


## wg-easy

1. Create a bcrypt password:
    ```
    docker run -it ghcr.io/wg-easy/wg-easy wgpw
    Enter your password:      // hidden prompt, type in your password
    PASSWORD_HASH='$2b$12$coPqCsPtcFO.Ab99xylBNOW4.Iu7OOA2/ZIboHN6/oyxca3MWo7fW'
    ```

2. Edit/create `.env` file
3. Point a A record to your server
4. Open port 51820 in your firewall
5. `docker compose up -d`