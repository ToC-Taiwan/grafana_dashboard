# GRAFANA DASHBOARD

## Sample

![monitor_sample](./assets/monitor_sample.png "monitor_sample")

## Source Name

- Prometheus(default): `PrometheusProduction`
  - URL: `http://172.20.10.72:9090`
- Loki: `LokiProduction`
  - URL: `http://172.20.10.82:3100`

- Postgres: `TradeBotPostgreSQL`
  - Host: `172.20.10.10:5432`
  - Database: `trade_agent`
  - User: `postgres`
  - Password: `asdf0000`
  - TLS: `disable`
  - Version: `12+`
