# grafana-dashboards
Grafana dashboards for the 42Network Grafana monitoring system

## Deployment Instructions

```
git clone https://github.com/42School/grafana-dashboards.git /opt/grafana-dashboards
mv /opt/grafana-dashboards/monitoring.yaml /etc/grafana/provisioning/dashboards
service grafana-server restart
```
