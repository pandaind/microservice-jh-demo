# JHipster generated Docker-Compose configuration

## Usage

Launch all your infrastructure by running: `docker-compose up -d`.

## Configured Docker services

### Service registry and configuration server:

- [JHipster Registry](http://localhost:8761)

### Applications and dependencies:

- simplehotel (gateway application)
- simplehotel's postgresql database
- reservationsvc (microservice application)
- reservationsvc's postgresql database
- roomservice (microservice application)
- roomservice's postgresql database

### Additional Services:

- [Prometheus server](http://localhost:9090)
- [Prometheus Alertmanager](http://localhost:9093)
- [Grafana](http://localhost:3000)
