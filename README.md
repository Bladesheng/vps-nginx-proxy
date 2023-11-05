# vps-nginx-proxy

This repo contains docker-compose that runs nginx-proxy and acme-companion on my VPS.

-   nginx-proxy: for hosting multiple apps on a single server
-   acme-companion: for handling SSL certificates automatically

## How to run this

-   Clone the repo, then create `.env` file - see [`.env.example`](https://github.com/Bladesheng/weather-station-backend/blob/main/.env.example)

-   Install [Grafana Loki Docker driver client](https://grafana.com/docs/loki/latest/send-data/docker-driver/) for logs storage

-   Run docker compose:

```sh
docker compose up
```
