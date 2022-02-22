```bash
kubectl create namespace grafana
```

```bash
kubectl apply -f https://raw.githubusercontent.com/cfoos/Grafana/main/grafanapvc.yaml
```

```bash
kubectl apply -f https://raw.githubusercontent.com/cfoos/Grafana/main/grafanadeployment.yaml
```

```bash
kubectl apply -f https://raw.githubusercontent.com/cfoos/Grafana/main/grafanaservice.yaml
```

```bash
ceph orch apply prometheus --placement 'count:3'
ceph mgr module enable prometheus
```

prometheus ceph data sources
http://192.168.2.101:9095
http://192.168.2.102:9095
http://192.168.2.103:9095
