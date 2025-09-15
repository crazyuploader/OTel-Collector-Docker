# OpenTelemetry Collector Docker

> An example of running OTel Collector in Docker.

This repository contains example(s) of running OTel Collector using Docker Compose.

## Notes

- Collector used here is OpenTelemetry Collector Contrib (also known as "otelcol-contrib"), more info [here](https://github.com/open-telemetry/opentelemetry-collector-releases/blob/main/distributions/otelcol-contrib).

- **Docker Image:** `otel/opentelemetry-collector-contrib:0.135.0`

- **Ports Exposed:**
  - HTTP: `4319`
  - GRPC: `4320`

- Kindly set **OTLP Endpoint** [here](https://github.com/crazyuploader/OTel-Collector-Docker/blob/main/config/config.yaml#L13) for the Exporter.
