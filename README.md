# Linux Application Monitoring Lab

## Overview

This project demonstrates a Linux application monitoring platform built with Docker, Prometheus, Grafana, Node Exporter, NGINX, and Blackbox Exporter.

The environment provides real-time infrastructure monitoring and application availability monitoring for a containerized Linux web application.

## Technologies Used

* Docker
* Docker Compose
* Prometheus
* Grafana
* Node Exporter
* Blackbox Exporter
* NGINX
* PromQL
* Linux

## Architecture

Docker Environment

* NGINX Web Application
* Node Exporter
* Blackbox Exporter

Monitoring Stack

* Prometheus
* Grafana

Prometheus collects Linux system metrics through Node Exporter and monitors application availability through Blackbox Exporter. Grafana visualizes infrastructure and application health through custom dashboards.

## Features

### Linux Infrastructure Monitoring

* CPU Usage Monitoring
* Memory Usage Monitoring
* Disk Usage Monitoring
* Linux Target Health

### Application Monitoring

* NGINX Web Application Availability
* HTTP Endpoint Monitoring
* Application Health Verification

### Observability

* Prometheus Metrics Collection
* PromQL Queries
* Grafana Dashboard Visualization
* Blackbox HTTP Probing

## Example PromQL Query

```promql
probe_success{job="nginx-web-check"}
```

This query verifies that the NGINX web application is reachable and returning a successful HTTP response.

## Skills Demonstrated

* Linux Administration
* Docker Containerization
* Docker Compose
* Infrastructure Monitoring
* Application Monitoring
* Observability
* Prometheus
* Grafana
* Blackbox Exporter
* NGINX Administration
* PromQL

## Screenshots

This repository includes:

* Prometheus Targets
* Linux Monitoring Dashboard
* NGINX Availability Queries
* Docker Container Deployment

## Future Enhancements

* NGINX Metrics Exporter
* Response Time Monitoring
* Alertmanager Integration
* Email Notifications
* Multi-Application Monitoring
* Multi-Host Monitoring

