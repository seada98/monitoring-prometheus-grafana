# Monitoring Stack with Prometheus and Grafana

## 📖 Overview
This project sets up a full monitoring environment using Docker Compose.  
It includes Prometheus, Node Exporter, and Grafana for system monitoring and visualization.

## ⚙️ Components
- **Prometheus:** collects system metrics.
- **Node Exporter:** exposes host metrics.
- **Grafana:** visualizes data in dashboards.

## 🚀 Run the Stack
```bash
docker compose up -d
```

## Then open:

- Prometheus → 
```bash
http://localhost:9090
```
- Node Exporter →
```bash
http://localhost:9100
```
- Grafana →
```bash
http://localhost:3000
- (admin / admin)
```

## 📊 Create Dashboard

- **Login to Grafana.**
- **Add Prometheus data source: http://prometheus:9090.**
- **Import the node_dashboard.json file.**

## 📬 Result
You’ll see real-time CPU and memory usage graphs!