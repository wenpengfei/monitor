# monitor
This docker-compose file will deploy these components:

- [traefik](https://traefik.io/)
- [prometheus](https://prometheus.io/)
- [node-exporter](https://github.com/prometheus/node_exporter)
- [grafana](https://grafana.com/)

## What you will need

- Docker Installation
- 3 A records for grafana, prometheus and traefik dashboard, and replace `.env` file's HOST_NAME environment variable

## Before docker-compose up

```
chmod 600 acme.json
docker network create web
```
