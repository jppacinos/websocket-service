## WebSocket Service

> This app is made possible by [Soketi](https://github.com/soketi/soketi) and [Docker](https://www.docker.com).

The service is designed with `MySQL` as the app manager driver and `Redis` as an adapter and cache driver in mind and needs additional configuration for customization.

---

### How to setup

- Copy `.env.example` to `.env` and update its contents
- Run the application: `docker compose up -d` or `docker compose -f docker-compose.local.yml up -d` (debug)
- Stop the application: `docker compose down`
