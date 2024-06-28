# Docker compose metrics with cAdvisor

This project contains a docker composition using
the Google container advisor to provide local docker container metrics.

These metrics are scraped by prometheus and made available a grafana dashboard.

A final Nginx-driven redirect opens the grafana board in Kiosk mode.

**DISCLAIMER**: This is meant for local workstation use for on-demand resource review.
There are no security-related restrictions, nothing is encrypted or protected.


## Available web services of the composition

cadvisor frontend: http://localhost:8080
prometheus frontend: http://localhost:9090
grafana frontend: http://localhost:3000
nginx frontend for kiosk mode: http://localhost:7080
