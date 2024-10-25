# prometheus-grafana

This repo will install the following containers:

prometheus
node_exporter
cadvisor
grafana

Prometheus is already configured to use the included prometheus.yaml file to collect data from the node_exporter and cadvisor exporters

To connect Grafana to Prometheus as a datasource use the server URL http://prometheus:9090

I suggest the below Grafana dashboards for the included exporters:

https://grafana.com/grafana/dashboards/1860-node-exporter-full/
https://grafana.com/grafana/dashboards/19908-docker-container-monitoring-with-prometheus-and-cadvisor/

# Install:

1. run the commands from the mount_root.txt to allow node_exporter to access host root directory
2. sudo docker-compose up -d --build
3. ???
4. PROFIT $$$