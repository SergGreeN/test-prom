### The following components are installed
  1. Grafana
  2. Prometheus
  3. Blackbox exporter
  
Blackbox exporter direct to endpoint (google.com).
Dashboard [13659](https://grafana.com/grafana/dashboards/13659-blackbox-exporter-http-prober/) added to Grafana.
Password to Grafana as it was specified in the file for the test task.

As Control plane was used kind version 1.20.12


### Clone repo

```
git clone https://github.com/SergGreeN/test-prom.git
```

```
cd test-prom/
```

### Build dependency

```
helm dependency build
```

### Install helm chart

```
helm install test1 . --namespace unitest --create-namespace --wait
```

