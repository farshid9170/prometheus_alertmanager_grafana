# prometheus_alertmanager_grafana


Here is a sample Git readme for the Prometheus-Alertmanager-Grafana stack:


This project sets up a monitoring and alerting stack using [Prometheus](https://prometheus.io), [Alertmanager](https://prometheus.io/docs/alerting/alertmanager/), and [Grafana](https://grafana.com/) for visualization.


This stack consists of the following components:

- Prometheus: a time-series database for metrics and monitoring data.
- Alertmanager: a tool for managing alerts and sending notifications based on defined rules.
- Grafana: a platform for data visualization and analytics.


## Configuration


run docker-compose.yml


you can find your favorites rules from rules.yml_awesome and replace them in prometheus rules.yml


also add your favorite exporters into the prometheus.conf


for recieve alert notification you must config the alertmanager.conf (this is just sample how to do this)



