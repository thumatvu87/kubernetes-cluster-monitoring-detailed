
# Kubernetes Cluster Monitoring with Prometheus, Grafana, and Alertmanager

This project sets up a full observability stack in Kubernetes using Prometheus, Grafana, Node Exporter, and Alertmanager.

## Features
- Real-time pod-level and node-level metrics
- Alert rules for CPU, memory, and pod status
- Custom dashboards in Grafana
- Service discovery and static targets for Prometheus
- Sample screenshots and targets config in /docs

## Tools Used
- Kubernetes
- Prometheus
- Grafana
- Alertmanager
- Node Exporter

## Structure
- k8s/: Manifests for deploying Prometheus, Grafana, Node Exporter
- monitoring/: Config files for alerting, dashboards, scrape configs
- docs/: Logs, screenshots, Prometheus target examples

## How to Use
1. Apply all files in the k8s/ directory
2. Port-forward Grafana (default port 3000) and login (admin/admin)
3. Import dashboard JSON from /monitoring
4. Validate alerts in Prometheus & Alertmanager
