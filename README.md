# Prometheus Hands-On
A simple application from the Go client library that emits random
latencies so that Prometheus pulls these metrics.

## Setup

Use docker-compose to start both application and prometheus

```
docker-compose up
```

Now you can access application on:

* http://localhost:8080/metrics
* http://localhost:9090/graph
