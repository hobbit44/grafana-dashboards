# Grafana Dashboards

This is a collection of the dashboards from [kube-prometheus-stack](https://github.com/prometheus-community/helm-charts/tree/main/charts/kube-prometheus-stack) stack that have been converted to be compatible with the [Grafana Operator](https://github.com/grafana/grafana-operator).

### Values

There is some templating done in the stack so below are the settings i used:

```
grafana.defaultDashboardsEditable = true
grafana.defaultDashboardsInterval = 1m
grafana.defaultDashboardsTimezone = UTC
grafana.sidecar.dashboards.multicluster.global.enabled = false
grafana.sidecar.dashboards.multicluster.etcd.enabled = false
```
