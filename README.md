# Prometheus & Grafana - docker-compose stack
Small collection with an example of how to launch prometheus and grafana. 

It includes:

* Grafana
* Prometheus
* Node Exporter

The example fully configures Grafana with access to Prometheus by default. The default username and password for Grafana here is:

```
Username: admin
Password: foobar
```

So all you need to do is start creating dashboards, or configure new application targets using the prometheus config file.

## Requirements

At the time of writing all you need is:

* Docker

## Run Instructions

1. `docker compose up -d`