# OpenTelemetry Collector Docker

> An example of running OTel Collector in Docker.

This repository contains example(s) of running OTel Collector using Docker Compose.

## Usage

After setting configuration in [`config.yaml`](config/config.yaml), simply bring up the Docker Container by running -

```bash
docker compose up --detach
```

### Notes

- Collector used here is ***OpenTelemetry Collector Contrib (also known as "otelcol-contrib")***, more info [here](https://github.com/open-telemetry/opentelemetry-collector-releases/blob/main/distributions/otelcol-contrib).

- **Docker Image:** `otel/opentelemetry-collector-contrib:0.142.0`

- **Ports Exposed:**
  - HTTP: `4319`
  - GRPC: `4320`

- Kindly set **OTLP Endpoint** [here](https://github.com/crazyuploader/OTel-Collector-Docker/blob/main/config/config.yaml#L14) for the Exporter.
