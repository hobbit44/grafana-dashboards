# Grafana Dashboards

This is a collection of the dashboards from kube-prometheus stack that have been converted to be compatible with the Grafana Operator.

### Values

There is some templating done in the stack so below are the settings i used:

```
grafana.defaultDashboardsEditable = true
grafana.defaultDashboardsInterval = 1m
grafana.defaultDashboardsTimezone = UTC
grafana.sidecar.dashboards.multicluster.global.enabled = false
grafana.sidecar.dashboards.multicluster.etcd.enabled = false
```
