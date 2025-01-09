# Labels Cross Reference for Prometheus & Loki

This project creates Prometheus and Loki instances that share some common labels.

## Config

To prevent conflicts with your other services:

- the Prometheus instance is exposed on port `9098`
- the Loki instance is exposed on port `3108`

## Getting started

```cli
docker compose up -d
```
