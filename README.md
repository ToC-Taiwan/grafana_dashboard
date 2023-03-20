# GRAFANA DASHBOARD

## Sample

![monitor_sample](./assets/monitor_sample.png "monitor_sample")

## Source Name

- Prometheus(default): `http://172.20.10.83:9090`
- Loki: `http://172.20.10.82:3100`

- Postgres: `TradeBotPostgreSQL`
  - Host: `172.20.10.10:5432`
  - Database: `trade_agent`
  - User: `postgres`
  - Password: `asdf0000`
  - TLS: `disable`
  - Version: `12+`

## Get all data sources

- URL: `/api/datasources`(GET)
